---
title: "IOcrConnector"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert methoden die nodig zijn om OCR toe te passen op afbeeldingsdocumenten en ingesloten afbeeldingen."
type: docs
weight: 13
url: /nl/java/com.groupdocs.conversion.integration.ocr/iocrconnector/
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

