---
title: "NoteLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов One."
type: docs
weight: 27
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

Параметры загрузки документов One.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NoteLoadOptions()](#NoteLoadOptions--) | Инициализирует новый экземпляр класса [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Шрифт по умолчанию для документа Note. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Шрифт по умолчанию для документа Note. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Заменять определённые шрифты при конвертации документа Note. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Заменять определённые шрифты при конвертации документа Note. |
| [getPassword()](#getPassword--) | Установить пароль для снятия защиты с защищённого документа. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установить пароль для снятия защиты с защищённого документа. |
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


Инициализирует новый экземпляр класса [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions).

### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


Тип файла входного документа

**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Шрифт по умолчанию для документа Note. Следующий шрифт будет использован, если шрифт отсутствует.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Шрифт по умолчанию для документа Note. Следующий шрифт будет использован, если шрифт отсутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Заменять определённые шрифты при конвертации документа Note.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Заменять определённые шрифты при конвертации документа Note.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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

