---
title: "PdfLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Pdf."
type: docs
weight: 31
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfLoadOptions extends LoadOptions implements Serializable
```

Параметры загрузки документов Pdf.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) | Инициализирует новый экземпляр класса [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Удалить встроенные файлы. |
| [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Удалить встроенные файлы. |
| [getPassword()](#getPassword--) | Установить пароль для снятия защиты с защищённого документа. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установить пароль для снятия защиты с защищённого документа. |
| [getDefaultFont()](#getDefaultFont--) | Шрифт по умолчанию для PDF‑документа. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Шрифт по умолчанию для PDF‑документа. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Заменять определённые шрифты при преобразовании PDF‑документа. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Заменять определённые шрифты при преобразовании PDF‑документа. |
| [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Скрывать аннотации в PDF‑документах. |
| [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Скрывать аннотации в PDF‑документах. |
| [getFlattenAllFields()](#getFlattenAllFields--) | Свести все поля PDF‑формы. |
| [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Свести все поля PDF‑формы. |
| [getResetFontFolders()](#getResetFontFolders--) | Сбросить папки шрифтов перед загрузкой документа |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Инициализирует новый экземпляр класса [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).

### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Тип файла входного документа

**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Удалить встроенные файлы.

**Returns:**
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Удалить встроенные файлы.

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Шрифт по умолчанию для PDF‑документа. Следующий шрифт будет использован, если шрифт отсутствует.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Шрифт по умолчанию для PDF‑документа. Следующий шрифт будет использован, если шрифт отсутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Заменять определённые шрифты при преобразовании PDF‑документа.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Заменять определённые шрифты при преобразовании PDF‑документа.

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
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Скрывать аннотации в PDF‑документах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Свести все поля PDF‑формы.

**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Свести все поля PDF‑формы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

