---
title: "CadDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحتوي على بيانات تعريف مستند Cad"
type: docs
weight: 11
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

يحتوي على بيانات تعريف مستند Cad

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | العرض |
|
|  | [getHeight()](#getHeight--) | الارتفاع |
|
|  | [getLayouts()](#getLayouts--) | التخطيطات في المستند |
|
|  | [getLayers()](#getLayers--) | الطبقات في المستند |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


العرض


**Returns:**
int - العرض

### getHeight() {#getHeight--}
```
public int getHeight()
```


الارتفاع


**Returns:**
int - الارتفاع

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


التخطيطات في المستند


**Returns:**
java.util.List<java.lang.String> - التخطيطات في المستند

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


الطبقات في المستند


**Returns:**
java.util.List<java.lang.String> - الطبقات في المستند

