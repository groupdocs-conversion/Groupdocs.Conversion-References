---
title: IOcrConnector
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Defines methods that are required to apply OCR to image documents and embedded images.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.conversion.integration.ocr/iocrconnector/
---```
public interface IOcrConnector
```

Defines methods that are required to apply OCR to image documents and embedded images.
## Methods

| Method | Description |
| --- | --- |
| [recognize(System.IO.Stream imageStream)](#recognize-com.aspose.ms.System.IO.Stream-) | Does the OCR processing of an image, provided as a stream. |
### recognize(System.IO.Stream imageStream) {#recognize-com.aspose.ms.System.IO.Stream-}
```
public abstract RecognizedImage recognize(System.IO.Stream imageStream)
```


Does the OCR processing of an image, provided as a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | com.aspose.ms.System.IO.Stream | Stream, containing an image to process |

**Returns:**
[RecognizedImage](../../com.groupdocs.conversion.integration.ocr/recognizedimage) - Structured recognized text, containing lines, words and their bounding rectangles
