---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Presentation ドキュメントの読み込みオプション。"
type: docs
weight: 2770
url: /ja/net/groupdocs.conversion.options.load/presentationloadoptions/
---
## PresentationLoadOptions class

Presentation ドキュメントの読み込みオプション。

```csharp
public class PresentationLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IResourceLoadingOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PresentationLoadOptions](presentationloadoptions)() | 新しい[`PresentationLoadOptions`](../presentationloadoptions)クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearbuiltindocumentproperties) { get; set; } | ドキュメントから組み込みメタデータプロパティを削除します。 |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearcustomdocumentproperties) { get; set; } | ドキュメントからカスタムメタデータプロパティを削除します。 |
| [CommentsPosition](../../groupdocs.conversion.options.load/presentationloadoptions/commentsposition) { get; set; } | スライドにコメントが印刷される方法を表します。デフォルトは None です。 |
| [ConvertOwned](../../groupdocs.conversion.options.load/presentationloadoptions/convertowned) { get; set; } | [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) を実装します。既定は false です。 |
| [ConvertOwner](../../groupdocs.conversion.options.load/presentationloadoptions/convertowner) { get; set; } | [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) を実装します。既定は true です。 |
| [DefaultFont](../../groupdocs.conversion.options.load/presentationloadoptions/defaultfont) { get; set; } | プレゼンテーションのレンダリング用デフォルトフォントです。プレゼンテーションのフォントが欠落している場合、以下のフォントが使用されます。 |
| [Depth](../../groupdocs.conversion.options.load/presentationloadoptions/depth) { get; set; } | [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) を実装します。既定: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/presentationloadoptions/fontsubstitutes) { get; set; } | プレゼンテーション文書を変換する際に特定のフォントを置き換えます。 |
| [Format](../../groupdocs.conversion.options.load/presentationloadoptions/format) { get; set; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [NotesPosition](../../groupdocs.conversion.options.load/presentationloadoptions/notesposition) { get; set; } | スライドにノートが印刷される方法を表します。デフォルトは None です。 |
| [Password](../../groupdocs.conversion.options.load/presentationloadoptions/password) { get; set; } | 保護されたドキュメントの保護を解除するためのパスワードを設定します。 |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/presentationloadoptions/preservedocumentstructure) { get; set; } | PDF に変換する際にドキュメント構造を保持するかどうかを決定します（既定は false）。 |
| [ShowHiddenSlides](../../groupdocs.conversion.options.load/presentationloadoptions/showhiddenslides) { get; set; } | 非表示スライドを表示します。 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/presentationloadoptions/skipexternalresources) { get; set; } | 実装: [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/presentationloadoptions/whitelistedresources) { get; set; } | 実装: [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| [SetVideoConnector](../../groupdocs.conversion.options.load/presentationloadoptions/setvideoconnector)(IPresentationVideoConnector) | ビデオドキュメントコネクタを設定します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
