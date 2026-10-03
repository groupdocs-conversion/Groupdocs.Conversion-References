---
title: "ConvertedPageStream"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "रूपांतरित पृष्ठ स्ट्रीम प्राप्त करने वाले डेलीगेट का वर्णन करता है।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.conversion.contracts/convertedpagestream/
---```
public interface ConvertedPageStream
```

Describes delegate to receive converted page stream.

## Methods

| Method | Description |
| --- | --- |
| [invoke(String sourceFileName, FileType fileType, int pageNumber, System.IO.Stream stream)](#invoke-java.lang.String-com.groupdocs.conversion.filetypes.FileType-int-com.aspose.ms.System.IO.Stream-) | Receives converted page stream.
 |
### invoke(String sourceFileName, FileType fileType, int pageNumber, System.IO.Stream stream) {#invoke-java.lang.String-com.groupdocs.conversion.filetypes.FileType-int-com.aspose.ms.System.IO.Stream-}
```
public abstract System.IO.Stream invoke(String sourceFileName, FileType fileType, int pageNumber, System.IO.Stream stream)
```


Receives converted page stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileName | java.lang.String |  |
| fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| pageNumber | int | Converted page number
 |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
com.aspose.ms.System.IO.Stream - Returns converted page stream.

