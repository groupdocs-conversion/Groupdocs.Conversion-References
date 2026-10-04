---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "スプレッドシート ドキュメントを定義します。以下のファイルタイプが含まれます Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. スプレッドシート形式の詳細はherehttps//wiki.fileformat.com/spreadsheetでご確認ください。"
type: docs
weight: 1240
url: /ja/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

スプレッドシート ドキュメントを定義します。以下のファイルタイプが含まれます: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). スプレッドシート形式の詳細は[here](https://wiki.fileformat.com/spreadsheet)でご覧ください。

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | CSV（カンマ区切り値）拡張子のファイルは、カンマで区切られたデータレコードを含むプレーンテキストファイルを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/csv)でご確認ください。 |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF は Data Interchange Format の略で、異なるアプリケーション間でスプレッドシートデータをインポート/エクスポートするために使用されます。これには Microsoft Excel、OpenOffice Calc、StarCalc などが含まれます。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/dif)でご覧ください。 |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel は、ZIP パッケージではなくフラットな XML ファイルに格納された Office Open XML SpreadsheetML です。 |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | .fods 拡張子のファイルは、行と列にデータを格納する OpenDocument Spreadsheet ドキュメント形式の一種です。この形式は OASIS が公開・維持する ODF 1.2 仕様の一部として定義されています。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/fods)でご確認ください。 |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | .numbers 拡張子のファイルはスプレッドシート ファイルタイプに分類されるため、.xlsx ファイルと類似していますが、Numbers ファイルは Apple iWork Numbers スプレッドシート ソフトウェアで作成されます。このファイル形式の詳細は[here](https://docs.fileformat.com/spreadsheet/numbers)でご覧ください。 |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | ODS 拡張子のファイルは、ユーザーが編集可能な OpenDocument Spreadsheet ドキュメント形式を表します。データは ODF ファイル内の行と列に格納されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/ods)でご確認ください。 |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | .ots 拡張子のファイルは、Apache OpenOffice に含まれる Calc アプリケーションで作成された OpenDocument Spreadsheet テンプレート ファイルです。Calc アプリケーションは Microsoft Office の Excel に類似しています。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/ots)でご確認ください。 |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | SXC（Sun XML Calc）ファイル形式は OpenOffice.org というオフィススイートに属します。この形式は XML ベースのスプレッドシート ファイル形式で、ユーザーのスプレッドシートニーズに対応します。SXC 形式は数式、関数、マクロ、チャートに加えて DataPilot をサポートしています。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/sxc)でご覧ください。 |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | タブ区切り値（TSV）ファイル形式は、タブで区切られたデータをプレーンテキスト形式で表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/tsv)でご確認ください。 |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM は、スプレッドシートに新しい機能を追加するために使用されるマクロ対応アドイン ファイルです。アドインは追加のコードを実行し、スプレッドシートに追加機能を提供する補助プログラムです。このファイル形式の詳細は[here](https://docs.fileformat.com/spreadsheet/xlam/)でご覧ください。 |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS は Excel バイナリ ファイル形式を表します。このようなファイルは Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシート プログラムでも作成できます。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xls)でご確認ください。 |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB ファイル形式は、Excel ワークブックの内容を指定するレコードと構造の集合である Excel バイナリ ファイル形式を定義します。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xlsb)でご確認ください。 |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM はマクロをサポートするスプレッドシート ファイルの一種です。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xlsm)でご確認ください。 |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX は、Microsoft が Microsoft Office 2007 のリリースとともに導入した、Microsoft Excel ドキュメントの広く知られた形式です。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xlsx)でご確認ください。 |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | .XLT 拡張子のファイルは、Microsoft Office スイートの一部であるスプレッドシート アプリケーション Microsoft Excel で作成されたテンプレート ファイルです。Microsoft Office 97-2003 は新しい XLT ファイルの作成と開くことをサポートしていました。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xlt)でご確認ください。 |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM ファイル拡張子は、Microsoft Excel がマクロ対応テンプレート ファイルとして生成するファイルを表します。XLTM ファイルは構造上 XLTX と似ていますが、後者はマクロ付きテンプレートの作成をサポートしていません。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xltm)でご確認ください。 |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX ファイルは、Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレートを表します。これは、XLTX ファイルで指定された設定と同じ設定を持つ XLSX ファイルを生成するために使用できる標準テンプレート ファイルを作成するために使用されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xltx)でご確認ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
