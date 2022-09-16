---
title: RecognizedImage
second_title: GroupDocs.Conversion for Java API Reference
description: Represents text extracted from an image as a result of its recognition process.
type: docs
weight: 10
url: /java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Represents text, extracted from an image as a result of its recognition process.
## Constructors

| Constructor | Description |
| --- | --- |
| [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Initializes a new instance of the class, using a set of recognized lines. |
## Fields

| Field | Description |
| --- | --- |
| [EMPTY](#EMPTY) | Empty recognized image |
## Methods

| Method | Description |
| --- | --- |
| [getLines()](#getLines--) | Gets lines of text, with their fragments, recognized within the document. |
| [getText()](#getText--) | Gets textual equivalent of the structured text |
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Initializes a new instance of the class, using a set of recognized lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lines | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | an IEnumerable (e.g. a list or an array) of recognized lines |

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Empty recognized image

### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Gets lines of text, with their fragments, recognized within the document.

**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Gets textual equivalent of the structured text

**Returns:**
java.lang.String
