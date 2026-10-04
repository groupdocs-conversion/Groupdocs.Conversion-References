---
title: "TsvLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Tsv ドキュメントの読み込みオプション。"
type: docs
weight: 2850
url: /ja/net/groupdocs.conversion.options.load/tsvloadoptions/
---
## TsvLoadOptions class

Tsv ドキュメントの読み込みオプション。

```csharp
public sealed class TsvLoadOptions : SpreadsheetLoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [TsvLoadOptions](tsvloadoptions)() | [`TsvLoadOptions`](../tsvloadoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | AllColumnsInOnePagePerSheet が true の場合、1 シートのすべての列内容が結果の 1 ページに出力されます。pagesetup の用紙サイズの幅は無効になりますが、pagesetup の他の設定は引き続き有効です。 |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | 変換時にすべての行の幅を自動調整します。 |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | ユーザーがセル関連オブジェクトを変更したときに Excel ファイルの制限をチェックするかどうかを指定します。たとえば、Excel は 32K を超える文字列の入力を許可しません。32K を超える値を入力した場合、このプロパティが true であれば例外がスローされます。false の場合、入力した文字列をセルの値として受け入れ、後で CSV など他のファイル形式に完全な文字列を出力できるようにします。ただし、Excel ファイル形式として無効な値を設定した場合、後でブックを Excel 形式で保存すべきではありません。そうしないと、生成された Excel ファイルで予期しないエラーが発生する可能性があります。 |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | ドキュメントから組み込みメタデータプロパティを削除します。 |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | ドキュメントからカスタムメタデータプロパティを削除します。 |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | ワークシートを列でページ分割します。デフォルトは 0 で、ページ分割なしです。 |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) を実装します。既定は false です。 |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) を実装します。既定は true です。 |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | スプレッドシート以外の形式に変換する際に特定の範囲を変換します。例: "D1:F8"。 |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | ファイルがロードされた時点のシステムカルチャ情報を取得または設定します |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | スプレッドシートドキュメントの既定フォントです。フォントが見つからない場合は以下のフォントが使用されます。 |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) を実装します。既定: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | スプレッドシートドキュメントを変換する際に特定のフォントを置き換えます。 |
| [Format](../../groupdocs.conversion.options.load/tsvloadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | 数式計算エラーを無視するかどうかを示します。エラーはサポートされていない関数や外部リンクなどが原因となることがあります。デフォルトは false です。 |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | ページ余白設定 |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | OnePagePerSheet が true の場合、シートの内容は PDF ドキュメントの 1 ページに変換されます。デフォルト値は true です。 |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | True の場合、PDF に変換するときは印刷品質よりもファイルサイズが小さくなるように最適化されます。 |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | 保護されたドキュメントの保護を解除するためのパスワードを設定します。 |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | PDF に変換する際にドキュメント構造を保持するかどうかを決定します（既定は false）。 |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | シートに対するコメントの印刷方法を表します。デフォルトは PrintNoComments です。 |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | ドキュメントをロードする前にフォントフォルダーをリセットします |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | ワークシートを行でページ分割します。デフォルトは 0 で、ページ分割なしです。 |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | 変換対象シートのインデックス一覧です。インデックスは 0 ベースで指定する必要があります。 |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | 変換対象シート名 |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Excel ファイルを変換する際にグリッド線を表示します。 |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Excel ファイルを変換する際に非表示シートを表示します。 |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | ページサイズ設定 |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | 変換時に空の行と列をスキップします。デフォルトは True です。 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | 実装: [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | スプレッドシートドキュメントを変換する際にフッターをスキップします。デフォルト: false。 |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | スプレッドシートドキュメントを変換する際にヘッダーをスキップします。デフォルト: false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | 実装: [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | 現在のインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
