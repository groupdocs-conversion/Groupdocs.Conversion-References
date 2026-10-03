---
title: "CadDocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιέχει μεταδεδομένα εγγράφου CAD"
type: docs
weight: 11
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Περιέχει μεταδεδομένα εγγράφου CAD

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWidth()](#getWidth--) | πλάτος |
|
|  | [getHeight()](#getHeight--) | ύψος |
|
|  | [getLayouts()](#getLayouts--) | Διατάξεις στο έγγραφο |
|
|  | [getLayers()](#getLayers--) | Στρώματα στο έγγραφο |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| μέγεθος | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


πλάτος


**Returns:**
int - πλάτος

### getHeight() {#getHeight--}
```
public int getHeight()
```


ύψος


**Returns:**
int - ύψος

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


Διατάξεις στο έγγραφο


**Returns:**
java.util.List<java.lang.String> - διατάξεις στο έγγραφο

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


Στρώματα στο έγγραφο


**Returns:**
java.util.List<java.lang.String> - στρώματα στο έγγραφο

