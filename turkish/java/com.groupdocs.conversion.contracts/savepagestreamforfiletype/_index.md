---
title: "SavePageStreamForFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Dönüştürülmüş belge sayfasını akışa kaydeden temsilciyi açıklar."
type: docs
weight: 26
url: /tr/java/com.groupdocs.conversion.contracts/savepagestreamforfiletype/
---```
public interface SavePageStreamForFileType
```

Describes delegate for saving converted document page into stream.

## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, FileType fileType)](#invoke-int-com.groupdocs.conversion.filetypes.FileType-) | Saves converted document page into stream.
 |
### invoke(int pageNumber, FileType fileType) {#invoke-int-com.groupdocs.conversion.filetypes.FileType-}
```
public abstract OutputStream invoke(int pageNumber, FileType fileType)
```


Saves converted document page into stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Converted page number
 |
| fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Converted document type
 |

**Returns:**
java.io.OutputStream - Must return a stream where the converted document page will be saved

