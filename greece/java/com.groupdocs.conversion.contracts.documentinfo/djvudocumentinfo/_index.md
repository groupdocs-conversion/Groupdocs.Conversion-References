---
title: "DjVuDocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιέχει μεταδεδομένα εγγράφου DjVu"
type: docs
weight: 15
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Περιέχει μεταδεδομένα εγγράφου DjVu

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | Λαμβάνει την κάθετη ανάλυση |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Λαμβάνει την οριζόντια ανάλυση |
|
|  | [getOpacity()](#getOpacity--) | Λαμβάνει τη διαφάνεια της εικόνας |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| εικόνα | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| μέγεθος | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Λαμβάνει την κάθετη ανάλυση


**Returns:**
double - κάθετη ανάλυση

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Λαμβάνει την οριζόντια ανάλυση


**Returns:**
double - οριζόντια ανάλυση

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Λαμβάνει τη διαφάνεια της εικόνας


**Returns:**
float - διαφάνεια εικόνας

