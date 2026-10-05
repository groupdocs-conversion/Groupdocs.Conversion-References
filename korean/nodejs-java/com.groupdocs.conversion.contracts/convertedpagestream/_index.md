---
title: "ConvertedPageStream"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "변환된 페이지 스트림을 수신하는 대리자를 설명합니다."
type: docs
weight: 18
url: /ko/nodejs-java/com.groupdocs.conversion.contracts/convertedpagestream/
---```
public interface ConvertedPageStream
```

Describes delegate to receive converted page stream.
## Methods

| Method | Description |
| --- | --- |
| [invoke(String sourceFileName, FileType fileType, int pageNumber, System.IO.Stream stream)](#invoke-java.lang.String-com.groupdocs.conversion.filetypes.FileType-int-com.aspose.ms.System.IO.Stream-) | Receives converted page stream. |
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
| pageNumber | int | Converted page number |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
com.aspose.ms.System.IO.Stream - Returns converted page stream.
