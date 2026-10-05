---
title: "SaveDocumentStreamForFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Описывает делегат для сохранения преобразованного документа в поток."
type: docs
weight: 23
url: /ru/nodejs-java/com.groupdocs.conversion.contracts/savedocumentstreamforfiletype/
---```
public interface SaveDocumentStreamForFileType
```

Describes delegate for saving converted document into stream.
## Methods

| Method | Description |
| --- | --- |
| [invoke(FileType fileType)](#invoke-com.groupdocs.conversion.filetypes.FileType-) | Saves converted document into stream. |
### invoke(FileType fileType) {#invoke-com.groupdocs.conversion.filetypes.FileType-}
```
public abstract OutputStream invoke(FileType fileType)
```


Saves converted document into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Converted document type |

**Returns:**
java.io.OutputStream - Must return a stream where the converted document will be saved
