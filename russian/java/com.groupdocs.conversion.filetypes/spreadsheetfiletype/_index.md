---
title: "SpreadsheetFileType"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Определяет документы электронных таблиц."
type: docs
weight: 25
url: /ru/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

Определяет документы электронных таблиц. Включает следующие типы файлов:
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
Узнайте больше о форматах электронных таблиц [здесь](../https://wiki.fileformat.com/spreadsheet).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | Конструктор сериализации |
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [Xls](#Xls) | XLS представляет двоичный формат файлов Excel. |
|
|  | [Xlsx](#Xlsx) | XLSX — известный формат документов Microsoft Excel, который был представлен Microsoft вместе с выпуском Microsoft Office 2007. |
|
|  | [Xlsm](#Xlsm) | XLSM — тип файлов электронных таблиц, поддерживающих макросы. |
|
|  | [Xlsb](#Xlsb) | Формат файла XLSB определяет двоичный формат файлов Excel, представляющий собой набор записей и структур, описывающих содержимое книги Excel. |
|
|  | [Ods](#Ods) | Файлы с расширением ODS представляют формат документов OpenDocument Spreadsheet, который можно редактировать пользователем. |
|
|  | [Ots](#Ots) | Файл с расширением .ots — это шаблон электронных таблиц OpenDocument, созданный с помощью приложения Calc, включённого в Apache OpenOffice. |
|
|  | [Xltx](#Xltx) | Файл XLTX представляет шаблон Microsoft Excel, основанный на спецификациях формата файлов Office OpenXML. |
|
|  | [Xlt](#Xlt) | Файлы с расширением .XLT — это шаблоны, созданные в Microsoft Excel, приложении для работы с электронными таблицами, входящем в состав пакета Microsoft Office. |
|
|  | [Xltm](#Xltm) | Расширение файла XLTM представляет файлы, генерируемые Microsoft Excel как шаблоны с поддержкой макросов. |
|
|  | [Tsv](#Tsv) | Формат файлов Tab-Separated Values (TSV) представляет данные, разделённые табуляцией, в простом текстовом формате. |
|
|  | [Xlam](#Xlam) | XLAM — это файл надстройки с поддержкой макросов, используемый для добавления новых функций в электронные таблицы. |
|
|  | [Csv](#Csv) | Файлы с расширением CSV (Comma Separated Values) представляют собой простые текстовые файлы, содержащие записи данных со значениями, разделёнными запятыми. |
|
|  | [Fods](#Fods) | Файл с расширением .fods — это тип формата документов OpenDocument Spreadsheet, который хранит данные в строках и столбцах. |
|
|  | [Dif](#Dif) | DIF означает Data Interchange Format, используемый для импорта/экспорта данных электронных таблиц между различными приложениями. |
|
|  | [Sxc](#Sxc) | Формат файла SXC (Sun XML Calc) относится к офисному пакету под названием OpenOffice.org. |
|
|  | [Numbers](#Numbers) | Файлы с расширением .numbers классифицируются как тип файлов электронных таблиц, поэтому они похожи на файлы .xlsx; но файлы Numbers создаются с помощью программы Apple iWork Numbers для электронных таблиц. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


Конструктор сериализации


### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS представляет собой формат двоичного файла Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для электронных таблиц, такими как OpenOffice Calc или Apple Numbers.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xls).


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX — известный формат документов Microsoft Excel, который был представлен Microsoft вместе с выпуском Microsoft Office 2007.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xlsx).


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM — тип файлов электронных таблиц, поддерживающих макросы.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xlsm).


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


Формат файла XLSB определяет двоичный формат файлов Excel, представляющий собой набор записей и структур, описывающих содержимое книги Excel.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xlsb).


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


Файлы с расширением ODS обозначают формат документа электронных таблиц OpenDocument, который может редактироваться пользователем. Данные хранятся в файле ODF в виде строк и столбцов.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/ods).


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


Файл с расширением .ots — это шаблон электронных таблиц OpenDocument, созданный с помощью программного обеспечения Calc, включённого в Apache OpenOffice. Программное обеспечение Calc аналогично Excel, доступному в Microsoft Office.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/ots).


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


Файл XLTX представляет собой шаблон Microsoft Excel, основанный на спецификациях формата файлов Office OpenXML. Он используется для создания стандартного шаблона, который может быть использован для генерации файлов XLSX с теми же настройками, указанными в файле XLTX.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xltx).


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


Файлы с расширением .XLT — это шаблоны, созданные в Microsoft Excel, который является приложением для электронных таблиц и входит в пакет Microsoft Office. Microsoft Office 97‑2003 поддерживал создание новых файлов XLT, а также их открытие.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xlt).


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


Расширение файла XLTM обозначает файлы, генерируемые Microsoft Excel как шаблоны с поддержкой макросов. Файлы XLTM похожи на XLTX по структуре, за исключением того, что последние не поддерживают создание шаблонов с макросами.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xltm).


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Формат файлов Tab-Separated Values (TSV) представляет данные, разделённые табуляцией, в простом текстовом формате.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/tsv).


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM — это файл надстройки с поддержкой макросов, используемый для добавления новых функций в электронные таблицы. Надстройка — это дополнительная программа, которая выполняет дополнительный код и предоставляет дополнительный функционал для электронных таблиц.
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


Файлы с расширением CSV (Comma Separated Values) представляют собой простые текстовые файлы, содержащие записи данных со значениями, разделёнными запятыми.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/csv).


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


Файл с расширением .fods — это тип формата документа электронных таблиц OpenDocument, который хранит данные в виде строк и столбцов. Формат указан в спецификациях ODF 1.2, опубликованных и поддерживаемых OASIS. Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/fods).


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF означает Data Interchange Format, который используется для импорта/экспорта данных электронных таблиц между различными приложениями. К ним относятся Microsoft Excel, OpenOffice Calc, StarCalc и многие другие. Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/dif).


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


Формат файла SXC (Sun XML Calc) относится к офисному пакету под названием OpenOffice.org. Этот формат в основном обслуживает потребности пользователей в электронных таблицах, так как является основанным на XML форматом файлов электронных таблиц. Формат SXC поддерживает формулы, функции, макросы и диаграммы вместе с DataPilot. Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/sxc).


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


Файлы с расширением .numbers классифицируются как тип файлов электронных таблиц, поэтому они похожи на файлы .xlsx; но файлы Numbers создаются с помощью программного обеспечения Apple iWork Numbers для электронных таблиц. Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/spreadsheet/numbers).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Подготовлены параметры конвертации по умолчанию для типа файла


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
