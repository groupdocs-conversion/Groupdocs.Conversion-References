---
title: "CadDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Содержит метаданные CAD‑документа"
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Содержит метаданные CAD‑документа
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | ширина |
| [getHeight()](#getHeight--) | высота |
| [getLayouts()](#getLayouts--) | раскладки в документе |
| [getLayers()](#getLayers--) | слои в документе |
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| размер | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


ширина

**Returns:**
int - ширина
### getHeight() {#getHeight--}
```
public int getHeight()
```


высота

**Returns:**
int - высота
### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


раскладки в документе

**Returns:**
java.util.List<java.lang.String> - раскладки в документе
### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


слои в документе

**Returns:**
java.util.List<java.lang.String> - слои в документе
