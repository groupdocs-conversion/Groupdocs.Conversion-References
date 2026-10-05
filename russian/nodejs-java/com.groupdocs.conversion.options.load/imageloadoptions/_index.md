---
title: "ImageLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Image."
type: docs
weight: 23
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

Параметры загрузки документов Image.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageLoadOptions()](#ImageLoadOptions--) | Инициализирует новый экземпляр класса [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Шрифт по умолчанию для типов документов Psd, Emf, Wmf. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Шрифт по умолчанию для типов документов Psd, Emf, Wmf. |
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
| [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | Установить OCR‑соединитель изображения |
| [getResetFontFolders()](#getResetFontFolders--) | Сбросить папки шрифтов перед загрузкой документа |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


Инициализирует новый экземпляр класса [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions).

### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


Тип файла входного документа

**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Шрифт по умолчанию для типов документов Psd, Emf, Wmf. Следующий шрифт будет использован, если шрифт отсутствует.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Шрифт по умолчанию для типов документов Psd, Emf, Wmf. Следующий шрифт будет использован, если шрифт отсутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### isRecognitionEnabled() {#isRecognitionEnabled--}
```
public boolean isRecognitionEnabled()
```




**Returns:**
boolean
### getOcrConnector() {#getOcrConnector--}
```
public IOcrConnector getOcrConnector()
```




**Returns:**
[IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector)
### setOcrConnector(IOcrConnector ocrConnector) {#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-}
```
public void setOcrConnector(IOcrConnector ocrConnector)
```


Установить OCR‑соединитель изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | Экземпляр OCR‑соединителя |

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

