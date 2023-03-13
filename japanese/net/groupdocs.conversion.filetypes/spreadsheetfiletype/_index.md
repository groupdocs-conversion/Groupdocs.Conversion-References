---
title: SpreadsheetFileType
second_title: GroupDocs.Conversion for .NET API リファレンス
description: スプレッドシート ドキュメントを定義します次のファイル タイプが含まれます Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . スプレッドシート形式の詳細ここhttps//wiki.fileformat.com/spreadsheet.
type: docs
weight: 1050
url: /ja/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

スプレッドシート ドキュメントを定義します。次のファイル タイプが含まれます: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . スプレッドシート形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | シリアル化コンストラクター |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイル family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他のオブジェクトと比較します。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 文字列表現 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | CSV (カンマ区切り値) 拡張子を持つファイルは、カンマ区切り値を持つデータのレコードを含むプレーン テキスト ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/csv) |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF は、異なるアプリケーション間でスプレッドシート データをインポート/エクスポートするために使用される Data Interchange Format の略です。これらには、Microsoft Excel、OpenOffice Calc、StarCalc などがあります。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/dif) |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | 拡張子が .fods のファイルは、行と列にデータを格納する OpenDocument スプレッドシート ドキュメント形式の一種です。この形式は、OASIS によって公開および管理されている ODF 1.2 仕様の一部として指定されています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/fods) |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | 拡張子が .numbers のファイルはスプレッドシート ファイル タイプとして分類されるため、.xlsx ファイルに似ています。ただし、Numbers ファイルは Apple iWork Numbers 表計算ソフトウェアを使用して作成されます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/numbers) |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | ODS 拡張子を持つファイルは、ユーザーが編集可能な OpenDocument スプレッドシート ドキュメント形式を表します。データは ODF ファイル内に行と列に保存されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/ods) |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | 拡張子が .ots のファイルは、Apache OpenOffice に含まれる Calc アプリケーション ソフトウェアで作成された OpenDocument スプレッドシート テンプレート ファイルです。 Calc アプリケーション ソフトウェアは、Microsoft Office で利用できる Excel に似ています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/ots) |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | ファイル形式 SXC (Sun XML Calc) は、OpenOffice.org というオフィス スイートに属しています。この形式は、XML ベースのスプレッドシート ファイル形式であるため、通常、ユーザーのスプレッドシートのニーズに対応します。 SXC 形式は、DataPilot と共に数式、関数、マクロ、チャートをサポートします。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/sxc) |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Tab-Separated Values (TSV) ファイル形式は、プレーン テキスト形式のタブで区切られたデータを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/tsv) |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM は、新しい関数をスプレッドシートに追加するために使用されるマクロ対応アドイン ファイルです。アドインは、追加のコードを実行し、スプレッドシートに追加の機能を提供する補助プログラムです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/xlam/) |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS は Excel バイナリ ファイル形式を表します。このようなファイルは、Microsoft Excel だけでなく、OpenOffice Calc や Apple Numbers などの他の同様のスプレッドシート プログラムでも作成できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB ファイル形式は、Excel ブックのコンテンツを指定するレコードと構造のコレクションである Excel バイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsb) |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM は、マクロをサポートするスプレッドシート ファイルの一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsm) |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX は、Microsoft Office 2007 のリリースで Microsoft によって導入された Microsoft Excel ドキュメントのよく知られた形式です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsx) |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | 拡張子が .XLT のファイルは、Microsoft Office スイートの一部として提供されるスプレッドシート アプリケーションである Microsoft Excel で作成されたテンプレート ファイルです。 Microsoft Office 97-2003 では、新しい XLT ファイルの作成と開くことがサポートされていました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlt) |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM ファイル拡張子は、Microsoft Excel によってマクロ有効テンプレート ファイルとして生成されるファイルを表します。 XLTM ファイルの構造は XLTX に似ていますが、XLTX はマクロを使用したテンプレート ファイルの作成をサポートしていません。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xltm) |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX ファイルは、Office OpenXML ファイル形式の仕様に基づく Microsoft Excel テンプレートを表します。 XLTX ファイルで指定されたものと同じ設定を示す XLSX ファイルを生成するために利用できる標準テンプレート ファイルを作成するために使用されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xltx) |

### 関連項目

* class [FileType](../filetype)
* 名前空間 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
