---
title: "EBookFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "EBook ドキュメントを定義します。以下のファイルタイプが含まれます Epub./ebookfiletype/epubMobi./ebookfiletype/mobiAzw3./ebookfiletype/azw3"
type: docs
weight: 1110
url: /ja/net/groupdocs.conversion.filetypes/ebookfiletype/
---
## EBookFileType class

EBook ドキュメントを定義します。以下のファイルタイプが含まれます: [`Epub`](./epub)[`Mobi`](./mobi)[`Azw3`](./azw3)

```csharp
public sealed class EBookFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [EBookFileType](ebookfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Azw3](../../groupdocs.conversion.filetypes/ebookfiletype/azw3) | AZW3（Kindle Format 8 (KF8) とも呼ばれる）は、Amazon Kindle デバイス向けに開発された AZW 電子書籍デジタルファイル形式の改良版です。この形式は従来の AZW ファイルを拡張したもので、Kindle Fire デバイスでのみ使用され、先行のファイル形式である MOBI と AZW との下位互換性があります。このファイル形式の詳細は [こちら](https://docs.fileformat.com/ebook/azw3/) でご確認ください。 |
| static readonly [Epub](../../groupdocs.conversion.filetypes/ebookfiletype/epub) | EPUB 拡張子は、出版社と読者に標準的なデジタル出版形式を提供する電子書籍ファイル形式です。この形式は現在非常に一般的で、多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。このファイル形式の詳細は [こちら](https://wiki.fileformat.com/ebook/epub) でご確認ください。 |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/ebookfiletype/mobi) | MOBI ファイル形式は、最も広く使用されている電子書籍ファイル形式の一つです。この形式は古い OEB（Open Ebook Format）を拡張したもので、Mobipocket Reader の独自形式として使用されていました。このファイル形式の詳細は [こちら](https://wiki.fileformat.com/ebook/mobi) でご確認ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
