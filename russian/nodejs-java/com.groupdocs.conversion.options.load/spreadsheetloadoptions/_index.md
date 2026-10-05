---
title: "SpreadsheetLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Spreadsheet."
type: docs
weight: 35
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable
```

Параметры загрузки документов Spreadsheet.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Инициализирует новый экземпляр класса [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getSheets()](#getSheets--) | Получить имя листа для преобразования |
| [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Установить имя листа для конвертации |
| [getCultureInfo()](#getCultureInfo--) | Получить информацию о системной культуре в момент загрузки файла |
| [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Установить информацию о системной культуре в момент загрузки файла |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Шрифт по умолчанию для электронных таблиц. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Шрифт по умолчанию для электронных таблиц. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Подменять определённые шрифты при конвертации документа электронных таблиц. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Подменять определённые шрифты при конвертации документа электронных таблиц. |
| [getShowGridLines()](#getShowGridLines--) | Отображать линии сетки при конвертации файлов Excel. |
| [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Отображать линии сетки при конвертации файлов Excel. |
| [getShowHiddenSheets()](#getShowHiddenSheets--) | Отображать скрытые листы при конвертации файлов Excel. |
| [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Отображать скрытые листы при конвертации файлов Excel. |
| [getOnePagePerSheet()](#getOnePagePerSheet--) | Если OnePagePerSheet истинно, содержимое листа будет конвертировано в одну страницу PDF‑документа. |
| [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Если OnePagePerSheet истинно, содержимое листа будет конвертировано в одну страницу PDF‑документа. |
| [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Получает свойство AllColumnsInOnePagePerSheet |
| [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Устанавливает свойство AllColumnsInOnePagePerSheet |
| [getOptimizePdfSize()](#getOptimizePdfSize--) | Если True и происходит конвертация в PDF, процесс оптимизирован для меньшего размера файла, а не для качества печати. |
| [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Если True и происходит конвертация в PDF, процесс оптимизирован для меньшего размера файла, а не для качества печати. |
| [getConvertRange()](#getConvertRange--) | Конвертировать определённый диапазон при преобразовании в формат, отличный от электронных таблиц. |
| [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Конвертировать определённый диапазон при преобразовании в формат, отличный от электронных таблиц. |
| [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Пропускать пустые строки и столбцы при конвертации. |
| [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Пропускать пустые строки и столбцы при конвертации. |
| [getPassword()](#getPassword--) | Установить пароль для снятия защиты с защищённого документа. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установить пароль для снятия защиты с защищённого документа. |
| [getHideComments()](#getHideComments--) | Скрывать комментарии. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Скрывать комментарии. |
| [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Проверять ограничения Excel‑файла, когда пользователь изменяет связанные объекты ячеек. |
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
| [getSheetIndexes()](#getSheetIndexes--) | Получает список индексов листов для конвертации. |
| [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Устанавливает список индексов листов для конвертации. |
| [isAutoFitRows()](#isAutoFitRows--) | Автоматически подгонять высоту всех строк при конвертации |
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
| [getResetFontFolders()](#getResetFontFolders--) | Сбросить папки шрифтов перед загрузкой документа |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
| [deepClone()](#deepClone--) | Клонирует текущий экземпляр. |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Инициализирует новый экземпляр класса [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions).

### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Получить имя листа для преобразования

**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Установить имя листа для конвертации

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| листы | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Получить информацию о системной культуре в момент загрузки файла

**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Установить информацию о системной культуре в момент загрузки файла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Тип файла входного документа

**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Шрифт по умолчанию для электронных таблиц. Следующий шрифт будет использован, если шрифт отсутствует.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Шрифт по умолчанию для электронных таблиц. Следующий шрифт будет использован, если шрифт отсутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Подменять определённые шрифты при конвертации документа электронных таблиц.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Подменять определённые шрифты при конвертации документа электронных таблиц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Отображать линии сетки при конвертации файлов Excel.

**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Отображать линии сетки при конвертации файлов Excel.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Отображать скрытые листы при конвертации файлов Excel.

**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Отображать скрытые листы при конвертации файлов Excel.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Если OnePagePerSheet истинно, содержимое листа будет конвертировано в одну страницу PDF‑документа. Значение по умолчанию — false.

**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Если OnePagePerSheet истинно, содержимое листа будет конвертировано в одну страницу PDF‑документа. Значение по умолчанию — false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Получает свойство AllColumnsInOnePagePerSheet

**Returns:**
boolean - true, если все столбцы помещаются на одну страницу
### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Устанавливает свойство AllColumnsInOnePagePerSheet

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| allColumnsInOnePagePerSheet | boolean | свойство AllColumnsInOnePagePerSheet |

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Если True и происходит конвертация в PDF, процесс оптимизирован для меньшего размера файла, а не для качества печати.

**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Если True и происходит конвертация в PDF, процесс оптимизирован для меньшего размера файла, а не для качества печати.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Преобразовать конкретный диапазон при конвертации в формат, отличный от таблицы. Пример: "D1:F8".

**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Преобразовать конкретный диапазон при конвертации в формат, отличный от таблицы. Пример: "D1:F8".

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Пропускает пустые строки и столбцы при конвертации. По умолчанию True.

**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Пропускает пустые строки и столбцы при конвертации. По умолчанию True.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Установить пароль для снятия защиты с защищённого документа.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Установить пароль для снятия защиты с защищённого документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Скрывать комментарии.

**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Скрывать комментарии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Проверять ограничения файла Excel, когда пользователь изменяет связанные с ячейками объекты. Например, Excel не позволяет вводить строковое значение длиной более 32 КБ. Когда вы вводите значение длиннее 32 КБ, если это свойство установлено в true, вы получите исключение. Если свойство установлено в false, мы примем введённую строку как значение ячейки, чтобы позже вы могли вывести полное строковое значение в другие форматы файлов, такие как CSV. Однако, если вы задали значение, недопустимое для формата файла Excel, не следует сохранять рабочую книгу в формате Excel позже. В противном случае может возникнуть непредвиденная ошибка в сгенерированном файле Excel.

**Returns:**
boolean — флаг проверки ограничения
### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Получает список индексов листов для конвертации.

**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Устанавливает список индексов листов для конвертации. Индексы должны быть нулевыми.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Автоматически подгонять высоту всех строк при конвертации

**Returns:**
boolean
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| autoFitRows | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Сбросить папки шрифтов перед загрузкой документа

**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Клонирует текущий экземпляр.

**Returns:**
java.lang.Object -
