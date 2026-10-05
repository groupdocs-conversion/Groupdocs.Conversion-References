---
title: "ConvertedDocumentStream"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Dönüştürülmüş belge akışını alan temsilciyi açıklar."
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.conversion.contracts/converteddocumentstream/
---```
public interface ConvertedDocumentStream
```

Describes delegate to receive converted document stream.
## Methods

| Method | Description |
| --- | --- |
| [invoke(String sourceFileName, FileType fileType, System.IO.Stream stream)](#invoke-java.lang.String-com.groupdocs.conversion.filetypes.FileType-com.aspose.ms.System.IO.Stream-) | Receives converted document stream. |
### invoke(String sourceFileName, FileType fileType, System.IO.Stream stream) {#invoke-java.lang.String-com.groupdocs.conversion.filetypes.FileType-com.aspose.ms.System.IO.Stream-}
```
public abstract System.IO.Stream invoke(String sourceFileName, FileType fileType, System.IO.Stream stream)
```


Receives converted document stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileName | java.lang.String |  |
| fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
com.aspose.ms.System.IO.Stream - Returns converted document stream.
