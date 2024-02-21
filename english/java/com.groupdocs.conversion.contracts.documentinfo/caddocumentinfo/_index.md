---
title: CadDocumentInfo
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Contains Cad document metadata
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Contains Cad document metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | width |
| [getHeight()](#getHeight--) | height |
| [getLayouts()](#getLayouts--) | layouts in the document |
| [getLayers()](#getLayers--) | layers in the document |
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


width

**Returns:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```


height

**Returns:**
int - height
### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


layouts in the document

**Returns:**
java.util.List<java.lang.String> - layouts in the document
### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


layers in the document

**Returns:**
java.util.List<java.lang.String> - layers in the document
