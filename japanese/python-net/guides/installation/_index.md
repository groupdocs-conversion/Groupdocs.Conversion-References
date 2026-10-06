---
title: "インストール"
linkTitle: "Installation"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "Windows、Linux、macOS 上で .NET 経由で Python 用 GroupDocs.Conversion をインストールします — PyPI から、または事前にダウンロードした wheel から、Intel と Apple Silicon ビルドを含みます。"
type: docs
url: /ja/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion for Python via .NET は、[PyPI](https://pypi.org/project/groupdocs-conversion-net/) 上で事前ビルドされた wheel として配布されています。PyPI インデックスはサポートされている各プラットフォーム向けに個別の wheel をホストしており、`pip` が自動的に適切なものを選択します。

インストール前に、環境が [System Requirements]() トピックに記載されたサポート対象プラットフォームと Python バージョンに合致していることを確認してください。

## Install Package from PyPI

ターミナルを開き、対象プラットフォーム用のインストールコマンドを実行してください:

{{< tabs "install-pypi">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

コマンドを実行すると、以下のような出力が表示されます:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

wheel ファイル名には、使用している OS に合わせたプラットフォームサフィックスが含まれます — 例として、Ubuntu/Debian では `manylinux1_x86_64`、Apple Silicon では `macosx_11_0_arm64`、64 ビット Windows では `win_amd64` です。

## Add the Package to `requirements.txt`

再現性のある環境を作るために、`requirements.txt` にパッケージのバージョンを固定してください:

```txt
groupdocs-conversion-net==26.9.0
```

次に、すべての依存関係を一括でインストールします:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

ビルド環境が PyPI にアクセスできない場合は、[GroupDocs Releases website](https://releases.groupdocs.com/conversion/python-net/) から適切な wheel をダウンロードし、ローカルにインストールしてください。各リリースごとに以下の wheel が公開されています:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

ダウンロードした wheel をプロジェクトフォルダーに配置し、次にインストールしてください:

{{< tabs "install-wheel">}}
{{< tab "Windows (64-bit)" >}}
```ps
py -m pip install groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab "Linux (glibc)" >}}
```bash
python3 -m pip install groupdocs_conversion_net-26.9.0-py3-none-manylinux1_x86_64.whl
```
{{< /tab >}}
{{< tab "macOS (Apple Silicon)" >}}
```bash
python3 -m pip install groupdocs_conversion_net-26.9.0-py3-none-macosx_11_0_arm64.whl
```
{{< /tab >}}
{{< tab "macOS (Intel)" >}}
```bash
python3 -m pip install groupdocs_conversion_net-26.9.0-py3-none-macosx_10_14_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

期待される出力:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
