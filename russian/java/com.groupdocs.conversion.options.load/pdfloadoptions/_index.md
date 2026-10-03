---
title: "PdfLoadOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры загрузки документов PDF."
type: docs
weight: 27
url: /ru/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Параметры загрузки документов PDF.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Инициализирует новый экземпляр класса [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Удалить встроенные файлы. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Удалить встроенные файлы. |
|
|  | [getPassword()](#getPassword--) | Установить пароль для снятия защиты с защищённого документа. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Установить пароль для снятия защиты с защищённого документа. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Шрифт по умолчанию для PDF‑документа. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Шрифт по умолчанию для PDF‑документа. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Заменять определённые шрифты при конвертации PDF‑документа. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Заменять определённые шрифты при конвертации PDF‑документа. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Скрывать аннотации в PDF‑документах. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Скрывать аннотации в PDF‑документах. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | Свести все поля PDF‑формы. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Свести все поля PDF‑формы. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Сбросить папки шрифтов перед загрузкой документа. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Включить или отключить генерацию нумерации страниц в конвертированном документе. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Получает флаг Remove JavaScript. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Устанавливает флаг Remove JavaScript. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Указывает, следует ли конвертировать основной документ. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Указывает, следует ли конвертировать основной документ. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Указывает, следует ли конвертировать вложенные документы. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Указывает, следует ли конвертировать вложенные документы. |
|
|  | [getDepth()](#getDepth--) | Максимальная глубина обработки вложенных документов. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Максимальная глубина обработки вложенных документов. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Инициализирует новый экземпляр класса [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Тип файла входного документа.


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Удалить встроенные файлы.


**Returns:**
логический
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Удалить встроенные файлы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Шрифт по умолчанию для PDF‑документа.
Следующий шрифт будет использован, если шрифт отсутствует.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Шрифт по умолчанию для PDF‑документа.
Следующий шрифт будет использован, если шрифт отсутствует.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Заменять определённые шрифты при конвертации PDF‑документа.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Заменять определённые шрифты при конвертации PDF‑документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Скрывать аннотации в PDF‑документах.


**Returns:**
логический
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Скрывать аннотации в PDF‑документах.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Свести все поля PDF‑формы.


**Returns:**
логический
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Свести все поля PDF‑формы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Сбросить папки шрифтов перед загрузкой документа.


**Returns:**
логический
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resetFontFolders | логический |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Включить или отключить генерацию нумерации страниц в конвертированном документе. По умолчанию: false.


**Returns:**
логический
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isPageNumbering | логический |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Получает флаг Remove JavaScript.


**Returns:**
логический
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Устанавливает флаг Remove JavaScript.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| removeJavascript | логический |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Указывает, следует ли конвертировать основной документ.

По умолчанию
true
.


**Returns:**
логический
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Указывает, следует ли конвертировать основной документ.

По умолчанию
true
.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOwner | логический |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Указывает, следует ли конвертировать вложенные документы.

По умолчанию
false
.


**Returns:**
логический
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Указывает, следует ли конвертировать вложенные документы.

По умолчанию
false
.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOwned | логический |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Максимальная глубина обработки вложенных документов.

По умолчанию
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Максимальная глубина обработки вложенных документов.

По умолчанию
2
.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| depth | int |  |

