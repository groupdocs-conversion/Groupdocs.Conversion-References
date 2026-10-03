---
title: "SaveDocumentStreamForFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Décrit le délégué pour enregistrer le document converti dans le flux."
type: docs
weight: 24
url: /fr/java/com.groupdocs.conversion.contracts/savedocumentstreamforfiletype/
---```
public interface SaveDocumentStreamForFileType
```

Describes delegate for saving converted document into stream.

## Methods

| Method | Description |
| --- | --- |
| [invoke(FileType fileType)](#invoke-com.groupdocs.conversion.filetypes.FileType-) | Saves converted document into stream.
 |
### invoke(FileType fileType) {#invoke-com.groupdocs.conversion.filetypes.FileType-}
```
public abstract OutputStream invoke(FileType fileType)
```


Saves converted document into stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Converted document type
 |

**Returns:**
java.io.OutputStream - Must return a stream where the converted document will be saved

