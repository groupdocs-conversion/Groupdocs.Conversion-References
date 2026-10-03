---
title: "ConvertedDocumentStream"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "रूपांतरित दस्तावेज़ स्ट्रीम प्राप्त करने वाले डेलीगेट का वर्णन करता है।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.conversion.contracts/converteddocumentstream/
---```
public interface ConvertedDocumentStream
```

Describes delegate to receive converted document stream.

## Methods

| Method | Description |
| --- | --- |
| [invoke(String sourceFileName, FileType fileType, System.IO.Stream stream)](#invoke-java.lang.String-com.groupdocs.conversion.filetypes.FileType-com.aspose.ms.System.IO.Stream-) | Receives converted document stream.
 |
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

