---
title: "RtfOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры конвертации в тип файла RTF."
type: docs
weight: 39
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

Параметры конвертации в тип файла RTF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | Указывает, записываются ли ключевые слова для "старых читателей" в RTF или нет. |
| [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | Указывает, записываются ли ключевые слова для "старых читателей" в RTF или нет. |
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


Указывает, записываются ли ключевые слова для "старых читателей" в RTF или нет. Это может значительно влиять на размер RTF‑документа. По умолчанию — False.

**Returns:**
boolean
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


Указывает, записываются ли ключевые слова для "старых читателей" в RTF или нет. Это может значительно влиять на размер RTF‑документа. По умолчанию — False.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

