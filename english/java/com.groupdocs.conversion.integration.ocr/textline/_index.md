---
title: TextLine
second_title: GroupDocs.Conversion for Java API Reference
description: Represents text extracted from an image as a result of its recognition process.
type: docs
weight: 12
url: /java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Represents text, extracted from an image as a result of its recognition process.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Initializes a new instance of a line of text, extracted by OCR engine from an image. |
## Methods

| Method | Description |
| --- | --- |
| [getFragments()](#getFragments--) | Gets an array of text fragments, such as symbols and words, recognized in the line. |
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Initializes a new instance of a line of text, extracted by OCR engine from an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fragments | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | initial set of text fragments |

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Gets an array of text fragments, such as symbols and words, recognized in the line.

**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
