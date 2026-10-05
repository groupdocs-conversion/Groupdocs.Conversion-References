---
title: "DjVuDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Содержит метаданные DjVu‑документа"
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Содержит метаданные DjVu‑документа
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getVerticalResolution()](#getVerticalResolution--) | Получает вертикальное разрешение |
| [getHorizontalResolution()](#getHorizontalResolution--) | Получает горизонтальное разрешение |
| [getOpacity()](#getOpacity--) | Получает непрозрачность изображения |
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| размер | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Получает вертикальное разрешение

**Returns:**
double - вертикальное разрешение
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Получает горизонтальное разрешение

**Returns:**
double - горизонтальное разрешение
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Получает непрозрачность изображения

**Returns:**
float - непрозрачность изображения
