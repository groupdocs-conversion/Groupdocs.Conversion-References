---
title: CsvLoadOptions
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Опции для загрузки CSVдокументов.
type: docs
weight: 2050
url: /ru/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

Опции для загрузки CSV-документов.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | Инициализирует новый экземпляр[`CsvLoadOptions`](../csvloadoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Проверять ли ограничение файла excel, когда пользователь изменяет объекты, связанные с ячейками. Например, Excel не позволяет вводить строковое значение длиннее 32 КБ. Когда вы вводите значение длиннее 32 КБ, если это свойство истинно, вы получите исключение. Если это свойство имеет значение false, мы примем введенное вами строковое значение в качестве значения ячейки, чтобы позже вы могли вывести полное строковое значение для других форматов файлов, таких как CSV. Однако, если вы установили такое значение, которое недопустимо для формата файла Excel, вам не следует сохранять книгу в формате файла Excel позже. В противном случае может возникнуть непредвиденная ошибка для сгенерированного файла Excel. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | Указывает, преобразуется ли строка в файле в дату. По умолчанию Истина. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | Указывает, преобразуется ли строка в файле в числовой формат. По умолчанию Истина. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Преобразование определенного диапазона при преобразовании в формат, отличный от электронной таблицы. Пример: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Получить или установить информацию о культуре системы во время загрузки файла |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Шрифт по умолчанию для табличного документа. Если шрифт отсутствует, будет использоваться следующий шрифт. |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | Кодировка. По умолчанию используется Encoding.Default. . |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Замена определенных шрифтов при преобразовании табличного документа. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Тип файла входного документа. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | Указывает, является ли текст формулой, если он начинается с "=". |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Скрыть комментарии. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True означает, что файл содержит несколько кодировок. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Если OnePagePerSheet имеет значение true, содержимое листа будет преобразовано в одну страницу документа PDF. Значение по умолчанию — true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | При значении True и преобразовании в Pdf преобразование оптимизировано для лучшего размера файла, чем качество печати. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Установить пароль для снятия защиты с защищенного документа. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Разделитель CSV-файла. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Список индексов листов для преобразования. Индексы должны начинаться с нуля |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Имя листа для преобразования |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Показывать линии сетки при преобразовании файлов Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Показывать скрытые листы при преобразовании файлов Excel. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Пропускает пустые строки и столбцы при преобразовании. По умолчанию Истина. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Клонирует текущий экземпляр. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит хеш-функцией по умолчанию. |

### Смотрите также

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* пространство имен [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
