---
title: "FontFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "フォント文書を定義します。以下のタイプが含まれます Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 フォント形式の詳細は herehttps//docs.fileformat.com/font/ で確認できます。"
type: docs
weight: 1150
url: /ja/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

フォント文書を定義します。以下のタイプが含まれます: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) フォント形式の詳細は[こちら](https://docs.fileformat.com/font/)で確認できます。

```csharp
public sealed class FontFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [FontFileType](fontfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | 拡張子 .cff のファイルは Compact Font Format（CFF）で、PostScript Type 1 または CIDFont とも呼ばれます。CFF は複数のフォントを単一のフォントセット（FontSet）として格納するコンテナとして機能します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/font/cff/)で確認できます。 |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | 拡張子 .eot のファイルは、ドキュメントに埋め込まれる OpenType フォントです。主にウェブページなどのウェブファイルで使用されます。Microsoft が作成し、PowerPoint の .pps プレゼンテーションを含む Microsoft 製品でサポートされています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/font/eot/)で確認できます。 |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | 拡張子 .otf のファイルは OpenType フォント形式を指します。OTF フォントはスケーラビリティが高く、TTF 形式の既存機能を拡張してデジタルタイポグラフィに対応しています。Microsoft と Adobe が開発し、PostScript と TrueType の機能を組み合わせています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/font/otf/)で確認できます。 |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | 拡張子 .ttf のファイルは TrueType 仕様に基づくフォントファイルです。最初は Apple Computer, Inc. が Mac OS 用に設計・発売し、後に Microsoft が Windows OS 用に採用しました。このファイル形式の詳細は[こちら](https://docs.fileformat.com/font/ttf/)で確認できます。 |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Type 1 フォントは、かつてデスクトップ出版ソフトウェアや PostScript 対応プリンターで広く使用されていた Adobe の旧技術です。多くの最新プラットフォームやウェブブラウザ、モバイル OS ではサポートされていませんが、一部の OS ではまだ利用可能です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/font/type1/)で確認できます。 |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | 拡張子 .woff のファイルは Web Open Font Format（WOFF）に基づくウェブフォントファイルです。TrueType（.TTF）または OpenType（.OTT）フォントタイプのいずれかを圧縮したコンテナ形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/font/woff/)で確認できます。 |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | 拡張子 .woff のファイルは Web Open Font Format（WOFF）に基づくウェブフォントファイルです。TrueType（.TTF）または OpenType（.OTT）フォントタイプのいずれかを圧縮したコンテナ形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/font/woff/)で確認できます。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
