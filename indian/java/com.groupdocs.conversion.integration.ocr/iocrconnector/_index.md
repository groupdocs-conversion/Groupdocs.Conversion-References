---
title: "IOcrConnector"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "छवि दस्तावेज़ों और एम्बेडेड छवियों पर OCR लागू करने के लिए आवश्यक विधियों को परिभाषित करता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.conversion.integration.ocr/iocrconnector/
---```
public interface IOcrConnector
```

Defines methods that are required to apply OCR to image documents and embedded images.

## Methods

| Method | Description |
| --- | --- |
| [recognize(InputStream imageStream)](#recognize-java.io.InputStream-) | Does the OCR processing of an image, provided as a stream.
 |
### recognize(InputStream imageStream) {#recognize-java.io.InputStream-}
```
public abstract RecognizedImage recognize(InputStream imageStream)
```


Does the OCR processing of an image, provided as a stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Stream, containing an image to process
 |

**Returns:**
[RecognizedImage](../../com.groupdocs.conversion.integration.ocr/recognizedimage) - Structured recognized text, containing lines, words and their bounding rectangles

