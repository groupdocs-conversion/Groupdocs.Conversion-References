---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "メールドキュメントの読み込みオプション。"
type: docs
weight: 2500
url: /ja/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

メールドキュメントの読み込みオプション。

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | 新しい [`EmailLoadOptions`](../emailloadoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | 添付ファイルアイコンのリストを取得または設定します。このリストは、異なるファイルタイプに対して特定のアイコンを提供するようにカスタマイズできます。デフォルトでは、一般的なファイルタイプのアイコンが含まれています。 |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) を実装します。デフォルトは true です。 |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) を実装します。既定は true です。 |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) を実装します。 |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | メール文書のデフォルトフォントです。フォントが見つからない場合は、以下のフォントが使用されます。 |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) を実装します。既定: 1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | ヘッダーに添付ファイルを表示するか非表示にするかのオプションです。デフォルト: true。 |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | \"Bcc\" メールアドレスを表示するか非表示にするかのオプションです。デフォルト: false。 |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | \"Cc\" メールアドレスを表示するか非表示にするかのオプションです。デフォルト: false。 |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | メールアドレスを名前と一緒に表示するかどうかを制御するオプションです。例: \"John Doe &lt;john.doe@sample.com&gt;\" または単に \"John Doe.\" デフォルト: true。 |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | \"from\" メールアドレスを表示するか非表示にするかのオプションです。デフォルト: true。 |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | メールヘッダーを表示するか非表示にするかのオプションです。デフォルト: true。 |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | ヘッダーに送信日時を表示するか非表示にするかのオプションです。デフォルト: true。 |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | ヘッダーに件名を表示するか非表示にするかのオプションです。デフォルト: true。 |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | \"to\" メールアドレスを表示するか非表示にするかのオプションです。デフォルト: true。 |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | メールメッセージの [`EmailField`](../emailfield) とフィールドテキスト表現とのマッピングです。 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | フォント代替のリストです。 |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | ページ余白設定 |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | ページの向き設定 |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) を実装します。 |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | 保存時にメールメッセージの元の日時ヘッダー文字列を保持するかどうかを定義します（デフォルト値は true）。 |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | 外部リソースの読み込みタイムアウト |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | ページサイズ設定 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | 実装: [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | メッセージの日付に対する協定世界時 (UTC) オフセットを取得または設定します。このプロパティはローカル時間と UTC の時差を定義します。 |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | デフォルトの添付ファイルアイコンを使用するかどうかを取得または設定します。デフォルト: true。 |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | 実装: [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | 現在のインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
