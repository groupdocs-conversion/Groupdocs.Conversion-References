---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "WordProcessing ドキュメントの読み込みオプション。"
type: docs
weight: 2950
url: /ja/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

WordProcessing ドキュメントの読み込みオプション。

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | 新しいインスタンスの[`WordProcessingLoadOptions`](../wordprocessingloadoptions)クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | true（既定）に設定すると、テキストが主に右から左へ向かう段落やランのバイディフラグが変換前に修正されます。これは Microsoft Word および LibreOffice が使用するヒューリスティックと一致し、&lt;w:bidi/&gt; がなく、RTL スクリプトのみを含むランに &lt;w:rtl w:val="0"/&gt; が付与された状態で生成された（特に Google Docs が生成する）アラビア語/ヘブライ語ドキュメントのレンダリングを修正します。false に設定すると、ソースマークアップの厳密な OOXML 解釈を保持します。 |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | ブックマークオプション |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | ドキュメントから組み込みメタデータプロパティを削除します。 |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | ドキュメントからカスタムメタデータプロパティを削除します。 |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | 出力ドキュメントでコメントを表示する方法を指定します。既定は ShowInBalloons です。 |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) を実装します。既定は false です。 |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) を実装します。既定は true です。 |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | WordProcessing ドキュメントの既定フォントを設定します。 |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) を実装します。既定: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | EmbedTrueTypeFonts が true の場合、GroupDocs.Conversion は出力ドキュメントに TrueType フォントを埋め込みます。既定: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | システムの FontConfig に基づいて不足しているフォントを自動的に置き換えます。既定: false。 |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | ドキュメント内の FontInfo に基づいて不足しているフォントを自動的に置き換えます。既定: false。 |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | フォント名に基づいて不足しているフォントを自動的に置き換えます。既定: false。 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | WordsProcessing ドキュメントを変換する際に特定のフォントを置き換えます。 |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | ドキュメントの読み込みとフォント置換が完了した後、既存のフォントを変換します。フォント変換により、ロードに成功したフォントを含むドキュメント内のすべてのフォントを変更できます。 |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Word ドキュメントのマークアップと変更履歴を非表示にします。 |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | WordProcessing ドキュメントのハイフネーションオプションを設定します。 |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | 日付フィールドの元の値を保持します。既定: false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | ページ余白設定 |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | 変換されたドキュメントでページ番号の生成を有効または無効にします。既定: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | 保護されたドキュメントの保護を解除するためのパスワードを設定します。 |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | PDF に変換する際にドキュメント構造を保持するかどうかを決定します（既定は false）。 |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Microsoft Word のフォームフィールドを PDF でフォームフィールドとして保持するか、テキストに変換するかを指定します。既定は false です。 |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | コメントでコメント投稿者のフルネームを表示します。既定は false です。 |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | ページサイズ設定 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | 実装: [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | 読み込み後にフィールドを更新します。デフォルト: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | 読み込み後にページレイアウトを更新します。デフォルト: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | テキストシェイパーを使用してカーニング表示を改善するかどうかを指定します。デフォルトは false です。 |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | 実装: [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 備考

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• FontSubstitutes、DefaultFont、システム置換を使用して、欠落または利用できないフォントを処理します

• 処理順序: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• FontReplacements を使用して、読み込まれたドキュメント内の既存フォントを変更します

• すべてのフォント置換が完了した後に適用されます

### 関連項目

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
