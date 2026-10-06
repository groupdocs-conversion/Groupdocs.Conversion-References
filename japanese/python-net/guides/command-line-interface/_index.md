---
title: "コマンドラインインターフェイス"
linkTitle: "Command Line Interface"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "groupdocs-conversion コマンドラインツールを使用してターミナルから直接ドキュメントを変換します — Python スクリプトは不要です。ドキュメントを検査し、サポートされている形式を一覧表示し、ライセンスを適用するすべてをシェル上で行えます。"
type: docs
url: /ja/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


`groupdocs-conversion-net` パッケージをインストールすると、`groupdocs-conversion` コンソールスクリプトが `PATH` に配置されます。これは Python API の薄いラッパーで、Python スクリプトを起動するのが過剰になるケース（シェルパイプライン、Make ルール、CI ステップ、単発変換）向けに作られています。

## Prerequisites

CLI はパッケージに同梱されているため、追加インストールは不要です。`groupdocs-conversion-net` がインストールされていることを確認してください（[Quick Start Guide]() を参照）。その後、コンソールスクリプトが利用可能か確認します：

```bash
groupdocs-conversion --version
```

例えば `groupdocs-conversion 26.9.0` のように、パッケージのバージョンが表示されるはずです。

`groupdocs-conversion` コマンドが見つからない場合、パッケージのスクリプトディレクトリが `PATH` に含まれていない可能性があります。その代わりに Python モジュール形式で CLI を呼び出すこともできます：`python -m groupdocs.conversion`。この2つは同等です。

## Commands

CLI には4つのサブコマンドが用意されています。全フラグ一覧を見るには `groupdocs-conversion --help` を、特定のサブコマンドのヘルプを見るには `groupdocs-conversion <command> --help` を実行してください。

### convert

ドキュメントを別の形式に変換します。対象形式は出力ファイルの拡張子から推測されます。上書きしたい場合は `--format` を指定してください。

```bash
# 拡張子が対象形式を決定します
groupdocs-conversion convert business-plan.docx business-plan.pdf

# 出力名に有効な拡張子がない場合、形式を上書きしてください
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# 単一ページ（1から始まるインデックス）を変換します — ラスタターゲットに便利です
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# パスワードで保護されたソースを開く
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| オプション | 説明 |
| :- | :- |
| `--format` | 対象形式トークン（出力拡張子を上書きします）。 |
| `--password` | 保護されたソースドキュメントのパスワード。 |
| `--page` | 変換する最初のページ、1から始まるインデックスです。 |
| `--count` | 変換するページ数。 |

成功した場合、コマンドは出力パスを表示し、コード `0` で終了します。

### info

ドキュメントの基本情報—形式、サイズ、ページ数、利用可能な場合は作成日—を表示します。

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

保護されたソースには `--password` を使用します。

### list-formats

指定された入力ドキュメントに対してエンジンが生成できるすべてのターゲット形式を、一次ターゲットと二次ターゲットに分けて一覧表示します。

```bash
groupdocs-conversion list-formats business-plan.docx
```

保護されたソースには `--password` を使用します。

### list-all-formats

エンジンが認識している完全なソースからターゲットへの変換マトリックス（すべての入力形式と変換可能なターゲット）を表示します。

```bash
groupdocs-conversion list-all-formats
```

このコマンドは入力ファイルを受け取りません。

## Global options

これらのオプションはすべてのコマンドに適用されます：

| オプション | 説明 |
| :- | :- |
| `--license PATH` | コマンドを実行する前にライセンスファイルを適用します。 |
| `--version` | CLI のバージョンを表示して終了します。 |
| `--help` | 使用方法のヘルプを表示して終了します。 |

`--license` をサブコマンドの前に置くことで、事前にライセンスを適用します：

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

CLI は `GROUPDOCS_LIC_PATH` 環境変数も尊重します — 設定されている場合、ライセンスは自動的に適用され、`--license` を省略できます。詳細は [Licensing]() トピックをご覧ください。

## Format tokens

`convert` は出力拡張子 — または小文字に変換された `--format` の値 — を対応する変換オプションとファイルタイプにマッピングします。サポートされているトークンは次のとおりです：

| カテゴリ | トークン |
| :- | :- |
| PDF | `pdf` |
| 文書処理 | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| スプレッドシート | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| プレゼンテーション | `ppt`, `pptx`, `pptm`, `odp` |
| Web | `html`, `htm`, `mhtml` |
| 画像 | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| 電子書籍 | `epub`, `mobi`, `azw3` |

不明なトークンが原因でコマンドがコード `2` で終了し、受け入れられるトークンの一覧が表示されます。

## Exit codes

| コード | 意味 |
| :- | :- |
| `0` | 成功。 |
| `2` | ユーザーエラー — 不明な形式トークンまたは入力ファイルがありません。 |
| `1` | ランタイムエラー — 基本となる .NET 例外メッセージが標準エラーに出力されます。 |

これらのコードにより、シェルスクリプトや CI パイプラインで CLI を簡単に分岐させることができます。

## When to use the Python API instead

CLI は一般的な単一ドキュメント変換ケースをカバーしています。これを超える場合 — ページ単位のコールバック、インメモリストリーム、透かし、フォント、またはセル範囲オプション、さらにマルチドキュメントコンテナ階層 — は直接 Python API を使用してください。CLI フラグよりも豊富な機能を提供します。完全な機能セットについては、[Developer Guide]() を参照してください。

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
