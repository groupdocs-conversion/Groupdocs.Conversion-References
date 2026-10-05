---
title: "DiagramLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Diagram."
type: docs
weight: 16
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Параметры загрузки документов Diagram.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DiagramLoadOptions()](#DiagramLoadOptions--) | Инициализирует новый экземпляр класса [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Шрифт по умолчанию для документа Diagram. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Шрифт по умолчанию для документа Diagram. |
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Инициализирует новый экземпляр класса [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions).

### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Тип файла входного документа

**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Шрифт по умолчанию для документа Diagram. Следующий шрифт будет использован, если шрифт отсутствует.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Шрифт по умолчанию для документа Diagram. Следующий шрифт будет использован, если шрифт отсутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

