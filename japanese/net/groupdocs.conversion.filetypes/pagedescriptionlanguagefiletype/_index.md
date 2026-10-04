---
title: "PageDescriptionLanguageFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ページ記述ドキュメントを定義します。以下のファイルタイプが含まれます Svg./pagedescriptionlanguagefiletype/svgSvgz./pagedescriptionlanguagefiletype/svgzEps./pagedescriptionlanguagefiletype/epsCgm./pagedescriptionlanguagefiletype/cgmXps./pagedescriptionlanguagefiletype/xpsTex./pagedescriptionlanguagefiletype/texPs./pagedescriptionlanguagefiletype/psPcl./pagedescriptionlanguagefiletype/pclOxps./pagedescriptionlanguagefiletype/oxps"
type: docs
weight: 1190
url: /ja/net/groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
## PageDescriptionLanguageFileType class

ページ記述ドキュメントを定義します。以下のファイルタイプが含まれます: [`Svg`](./svg)[`Svgz`](./svgz)[`Eps`](./eps)[`Cgm`](./cgm)[`Xps`](./xps)[`Tex`](./tex)[`Ps`](./ps)[`Pcl`](./pcl)[`Oxps`](./oxps)

```csharp
public sealed class PageDescriptionLanguageFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PageDescriptionLanguageFileType](pagedescriptionlanguagefiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Cgm](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/cgm) | Computer Graphics Metafile (CGM) は、ベクタ画像（2D）、ラスタ画像、テキストの保存と交換のための、無料でプラットフォームに依存しない国際標準メタファイル形式です。CGM はオブジェクト指向アプローチと多数の機能を利用して画像を生成します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/cgm)をご覧ください。 |
| static readonly [Eps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/eps) | EPS 拡張子のファイルは、単一ページの外観を記述する Encapsulated PostScript プログラムを基本的に表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/eps)をご覧ください。 |
| static readonly [Oxps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/oxps) | OXPS ファイル形式は Open XML Paper Specification として知られています。これはページ記述言語およびドキュメント形式です。Microsoft がこの形式を開発しました。OXPS ファイル形式は PDF ファイルに非常に似ています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/page-description-language/oxps)をご覧ください。 |
| static readonly [Pcl](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/pcl) | PCL は Printer Command Language の略で、Hewlett Packard (HP) が導入したページ記述言語です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/pcl)をご覧ください。 |
| static readonly [Ps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/ps) | PostScript (PS) は、デスクトップおよび電子出版の分野で使用される汎用ページ記述言語です。PostScript (PS) の主な目的は、2 次元グラフィックデザインを支援することです。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/ps)をご覧ください。 |
| static readonly [Svg](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/svg) | SVG ファイルは、画像の外観を記述するために XML ベースのテキスト形式を使用する Scalar Vector Graphics ファイルです。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/svg)をご覧ください。 |
| static readonly [Svgz](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/svgz) | SVGZ ファイルは実際には SVG ファイルの圧縮版です。これにより、オンラインでのファイル配布が容易になります。SVG ファイルを .GZIP 圧縮アルゴリズムで圧縮すると、拡張子 .svgz が付与されます。 |
| static readonly [Tex](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/tex) | TeX は、プログラミング機能とマークアップ機能を備えた言語で、文書の組版に使用されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/tex)をご覧ください。 |
| static readonly [Xps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/xps) | XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。この形式は EMF ファイル形式の代替として Microsoft によって開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/xps)をご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
