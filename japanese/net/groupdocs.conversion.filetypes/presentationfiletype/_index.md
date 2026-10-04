---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "プレゼンテーションデータ（スライド、シェイプ、テキスト、アニメーション、ビデオ、オーディオ、埋め込みオブジェクト）を収容するためのレコードのコレクションを保存するプレゼンテーションファイル形式を定義します。以下のファイルタイプを含みます Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx。プレゼンテーション形式の詳細は herehttps//wiki.fileformat.com/presentation をご覧ください。"
type: docs
weight: 1210
url: /ja/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

プレゼンテーションデータ（スライド、シェイプ、テキスト、アニメーション、ビデオ、オーディオ、埋め込みオブジェクト）を収容するためのレコードのコレクションを保存するプレゼンテーションファイル形式を定義します。以下のファイルタイプを含みます: [`Odp`](./odp)、[`Otp`](./otp)、[`Pot`](./pot)、[`Potm`](./potm)、[`Potx`](./potx)、[`Pps`](./pps)、[`Ppsm`](./ppsm)、[`Ppsx`](./ppsx)、[`Ppt`](./ppt)、[`Pptm`](./pptm)、[`Pptx`](./pptx)。プレゼンテーション形式の詳細は[here](https://wiki.fileformat.com/presentation)をご覧ください。

```csharp
public sealed class PresentationFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | シリアライズ コンストラクタ |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイルファミリー |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他と比較します。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) を実装します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 文字列表現 |

## Fields

| 名前 | 説明 |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | FODP 拡張子のファイルは OpenDocument フラット XML プレゼンテーションを表します。プレゼンテーションファイルは OpenDocument 形式で保存されますが、標準の .ODP ファイルで使用される .ZIP コンテナの代わりにフラット XML 形式で保存されます。 |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | ODP 拡張子のファイルは OASIS Open 標準で OpenOffice.org が使用するプレゼンテーションファイル形式を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/odp)をご覧ください。 |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | .OTP 拡張子のファイルは OASIS OpenDocument 標準形式でアプリケーションが作成するプレゼンテーションテンプレートファイルを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/otp)をご覧ください。 |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | .POT 拡張子のファイルは PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレートファイルを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pot)をご覧ください。 |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | POTM 拡張子のファイルはマクロをサポートする Microsoft PowerPoint テンプレートファイルです。POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーションファイルを作成する際に使用できる既定設定が含まれています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/potm)をご覧ください。 |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | .POTX 拡張子のファイルは Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレートプレゼンテーションを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/potx)をご覧ください。 |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS（PowerPoint スライドショー）ファイルはスライドショー目的で Microsoft PowerPoint を使用して作成されます。PPS ファイルの読み取りおよび作成は Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pps)をご覧ください。 |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | PPSM 拡張子のファイルは Microsoft PowerPoint 2007 以降で作成されたマクロ対応スライドショー形式を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/ppsm)をご覧ください。 |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX（PowerPoint スライドショー）ファイルはスライドショー目的で Microsoft PowerPoint 2007 以降を使用して作成されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/ppsx)をご覧ください。 |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | PPT 拡張子のファイルはスライドショーとして表示するスライドのコレクションで構成された PowerPoint ファイルを表します。これは Microsoft PowerPoint 97-2003 が使用するバイナリファイル形式を指定しています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/ppt)をご覧ください。 |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | PPTM 拡張子のファイルは Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ対応プレゼンテーションファイルです。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pptm)をご覧ください。 |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | PPTX 拡張子のファイルは一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーションファイルです。以前のバイナリ形式の PPT とは異なり、PPTX 形式は Microsoft PowerPoint のオープン XML プレゼンテーションファイル形式に基づいています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pptx)をご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
