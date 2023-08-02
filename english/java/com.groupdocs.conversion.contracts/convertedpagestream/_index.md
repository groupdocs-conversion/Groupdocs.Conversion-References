---
title: ConvertedPageStream
second_title: GroupDocs.Conversion for Java API Reference
description: Describes delegate to receive converted page stream.
type: docs
weight: 18
url: /java/com.groupdocs.conversion.contracts/convertedpagestream/
---```
public interface ConvertedPageStream
```

Describes delegate to receive converted page stream.
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, System.IO.Stream stream, String sourceFileName)](#invoke-int-com.aspose.ms.System.IO.Stream-java.lang.String-) | Receives converted page stream. |
### invoke(int pageNumber, System.IO.Stream stream, String sourceFileName) {#invoke-int-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public abstract System.IO.Stream invoke(int pageNumber, System.IO.Stream stream, String sourceFileName)
```


Receives converted page stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Converted page number |
| stream | com.aspose.ms.System.IO.Stream |  |
| sourceFileName | java.lang.String |  |

**Returns:**
com.aspose.ms.System.IO.Stream - Returns converted page stream.
