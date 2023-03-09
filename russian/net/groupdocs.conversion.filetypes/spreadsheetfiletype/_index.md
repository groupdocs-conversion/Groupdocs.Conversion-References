---
title: SpreadsheetFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет электронные таблицы. Включает следующие типы файлов Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . Подробнее о форматах электронных таблицздесьhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 1050
url: /ru/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Определяет электронные таблицы. Включает следующие типы файлов: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Подробнее о форматах электронных таблиц[здесь](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Конструктор сериализации |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Файл family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит хеш-функцией по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Файлы с расширением CSV (значения, разделенные запятыми) представляют собой простые текстовые файлы, содержащие записи данных со значениями, разделенными запятыми. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF означает формат обмена данными, который используется для импорта/экспорта данных электронных таблиц между различными приложениями. К ним относятся Microsoft Excel, OpenOffice Calc, StarCalc и многие другие. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Файл с расширением .fods представляет собой тип формата документа OpenDocument Spreadsheet, в котором данные хранятся в строках и столбцах. Формат указан как часть спецификаций ODF 1.2, опубликованных и поддерживаемых OASIS. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/fods) . |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Файлы с расширением .numbers относятся к типу файлов электронных таблиц, поэтому они аналогичны файлам .xlsx; но файлы Numbers создаются с помощью программы электронных таблиц Apple iWork Numbers. Подробнее об этом формате файлов[здесь](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Файлы с расширением ODS обозначают формат документа электронной таблицы OpenDocument, который может редактировать пользователь. Данные хранятся в файле ODF в виде строк и столбцов. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Файл с расширением .ots представляет собой файл шаблона электронной таблицы OpenDocument, созданный с помощью прикладного программного обеспечения Calc, входящего в состав Apache OpenOffice. Программное обеспечение Calc аналогично Excel, доступному в Microsoft Office. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/ots) . |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Формат файла SXC (Sun XML Calc) принадлежит офисному пакету OpenOffice.org. Этот формат обычно отвечает потребностям пользователей в электронных таблицах, поскольку он представляет собой формат файла электронной таблицы на основе XML. Формат SXC поддерживает формулы, функции, макросы и диаграммы вместе с DataPilot. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/sxc) . |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Формат файла значений, разделенных табуляцией (TSV), представляет данные, разделенные табуляцией, в текстовом формате. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM — это файл надстройки с поддержкой макросов, который используется для добавления новых функций в электронные таблицы. Надстройка — это дополнительная программа, которая запускает дополнительный код и предоставляет дополнительные функции для электронных таблиц. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/xlam/) . |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS представляет формат двоичного файла Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими подобными программами для работы с электронными таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Формат файла XLSB указывает формат двоичного файла Excel, который представляет собой набор записей и структур, определяющих содержимое книги Excel. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM — это тип файлов электронных таблиц, поддерживающих макросы. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX — это широко известный формат документов Microsoft Excel, который был представлен Microsoft в выпуске Microsoft Office 2007. Узнайте больше об этом формате файлов[здесь](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Файлы с расширением .XLT представляют собой файлы шаблонов, созданные с помощью Microsoft Excel, который представляет собой приложение для работы с электронными таблицами, входящее в состав пакета Microsoft Office. Microsoft Office 97-2003 поддерживает создание новых файлов XLT, а также их открытие. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | Расширение файла XLTM представляет файлы, созданные Microsoft Excel, как файлы шаблонов с поддержкой макросов. Файлы XLTM аналогичны XLTX по структуре, за исключением того, что последний не поддерживает создание файлов шаблонов с макросами. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | Файл XLTX представляет собой шаблон Microsoft Excel, основанный на спецификациях формата файлов Office OpenXML. Он используется для создания стандартного файла шаблона, который можно использовать для создания файлов XLSX с теми же настройками, что и в файле XLTX. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xltx) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
