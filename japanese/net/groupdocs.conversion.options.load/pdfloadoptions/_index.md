---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Pdf ドキュメントの読み込みオプション。"
type: docs
weight: 2740
url: /ja/net/groupdocs.conversion.options.load/pdfloadoptions/
---
## PdfLoadOptions class

Pdf ドキュメントの読み込みオプション。

```csharp
public sealed class PdfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageNumberingLoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PdfLoadOptions](pdfloadoptions)() | 新しい [`PdfLoadOptions`](../pdfloadoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearbuiltindocumentproperties) { get; set; } | ドキュメントから組み込みメタデータプロパティを削除します。 |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearcustomdocumentproperties) { get; set; } | ドキュメントからカスタムメタデータプロパティを削除します。 |
| [ConvertOwned](../../groupdocs.conversion.options.load/pdfloadoptions/convertowned) { get; set; } | [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) を実装します。既定は false です。 |
| [ConvertOwner](../../groupdocs.conversion.options.load/pdfloadoptions/convertowner) { get; set; } | [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) を実装します。既定は true です。 |
| [DefaultFont](../../groupdocs.conversion.options.load/pdfloadoptions/defaultfont) { get; set; } | Pdf ドキュメントのデフォルトフォントです。フォントが見つからない場合は、以下のフォントが使用されます。 |
| [Depth](../../groupdocs.conversion.options.load/pdfloadoptions/depth) { get; set; } | [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) を実装します。既定: 1 |
| [FlattenAllFields](../../groupdocs.conversion.options.load/pdfloadoptions/flattenallfields) { get; set; } | PDF フォームのすべてのフィールドをフラット化します。 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/pdfloadoptions/fontsubstitutes) { get; set; } | Pdf ドキュメントを変換する際に特定のフォントを置き換えます。 |
| [FontTransformations](../../groupdocs.conversion.options.load/pdfloadoptions/fonttransformations) { get; set; } | ドキュメントの読み込みとフォント置換が完了した後、既存のフォントを変換します。フォント変換により、ロードに成功したフォントを含むドキュメント内のすべてのフォントを変更できます。 |
| [Format](../../groupdocs.conversion.options.load/pdfloadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [HidePdfAnnotations](../../groupdocs.conversion.options.load/pdfloadoptions/hidepdfannotations) { get; set; } | Pdf ドキュメントの注釈を非表示にします。 |
| [PageNumbering](../../groupdocs.conversion.options.load/pdfloadoptions/pagenumbering) { get; set; } | 変換されたドキュメントでページ番号の生成を有効または無効にします。既定: false |
| [Password](../../groupdocs.conversion.options.load/pdfloadoptions/password) { get; set; } | 保護されたドキュメントの保護を解除するためのパスワードを設定します。 |
| [RemoveEmbeddedFiles](../../groupdocs.conversion.options.load/pdfloadoptions/removeembeddedfiles) { get; set; } | 埋め込みファイルを削除します。 |
| [RemoveJavascript](../../groupdocs.conversion.options.load/pdfloadoptions/removejavascript) { get; set; } | JavaScript を削除します。 |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pdfloadoptions/resetfontfolders) { get; set; } | ドキュメントをロードする前にフォントフォルダーをリセットします |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
