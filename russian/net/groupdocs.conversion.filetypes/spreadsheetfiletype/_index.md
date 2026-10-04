---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет документы таблиц. Включает следующие типы файлов Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. Узнайте больше о форматах таблиц здесьhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /ru/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Определяет документы таблиц. Включает следующие типы файлов: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Узнайте больше о форматах таблиц [здесь](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Конструктор сериализации |

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Семейство файлов |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Реализует [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Файлы с расширением CSV (Comma Separated Values) представляют собой текстовые файлы, содержащие записи данных с запятыми в качестве разделителей. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF означает Data Interchange Format, который используется для импорта/экспорта данных таблиц между различными приложениями. К ним относятся Microsoft Excel, OpenOffice Calc, StarCalc и многие другие. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel — это Office Open XML SpreadsheetML, хранящийся в плоском XML‑файле вместо ZIP‑пакета. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Файл с расширением .fods — это тип формата документа OpenDocument Spreadsheet, который хранит данные в строках и столбцах. Формат определён в спецификации ODF 1.2, опубликованной и поддерживаемой OASIS. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Файлы с расширением .numbers классифицируются как тип файлов таблиц, поэтому они похожи на файлы .xlsx; однако файлы Numbers создаются с помощью программного обеспечения Apple iWork Numbers. Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Файлы с расширением ODS представляют собой формат документа OpenDocument Spreadsheet, который можно редактировать пользователем. Данные хранятся в ODF‑файле в виде строк и столбцов. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Файл с расширением .ots — это шаблон OpenDocument Spreadsheet, созданный с помощью приложения Calc, включённого в Apache OpenOffice. Приложение Calc аналогично Excel, доступному в Microsoft Office. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Формат файла SXC (Sun XML Calc) относится к офисному пакету под названием OpenOffice.org. Этот формат в основном удовлетворяет потребности пользователей в таблицах, так как является основанным на XML форматом файлов таблиц. Формат SXC поддерживает формулы, функции, макросы и диаграммы, а также DataPilot. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Формат файла Tab-Separated Values (TSV) представляет данные, разделённые табуляциями, в простом текстовом формате. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM — это файл надстройки с поддержкой макросов, который используется для добавления новых функций в электронные таблицы. Надстройка — это дополнительная программа, которая выполняет дополнительный код и предоставляет дополнительные возможности для электронных таблиц. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS представляет собой двоичный формат файлов Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для электронных таблиц, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Формат файла XLSB определяет двоичный формат файлов Excel, который представляет собой набор записей и структур, описывающих содержимое книги Excel. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM — это тип файлов электронных таблиц, поддерживающих макросы. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX — известный формат документов Microsoft Excel, который был представлен Microsoft вместе с выпуском Microsoft Office 2007. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Файлы с расширением .XLT являются шаблонными файлами, созданными в Microsoft Excel — приложении для электронных таблиц, входящем в состав пакета Microsoft Office. Microsoft Office 97‑2003 поддерживал создание новых файлов XLT, а также их открытие. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | Расширение файла XLTM обозначает файлы, генерируемые Microsoft Excel как шаблоны с поддержкой макросов. Файлы XLTM похожи на XLTX по структуре, за исключением того, что последние не поддерживают создание шаблонных файлов с макросами. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | Файл XLTX представляет собой шаблон Microsoft Excel, основанный на спецификациях формата файлов Office OpenXML. Он используется для создания стандартного шаблонного файла, который может быть использован для генерации файлов XLSX с теми же настройками, указанными в файле XLTX. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xltx). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
