---
title: TextFragment
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Represents a part of recognized text word symbol etc extracted by OCR engine.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Represents a part of recognized text (word, symbol, etc), extracted by OCR engine.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Initializes a new instance of the recognized text fragment. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets a textual content of the recognized text fragment. |
| [getRectangle()](#getRectangle--) | Gets a bounding rectangle of the recognized text fragment. |
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Initializes a new instance of the recognized text fragment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | textual content of the recognized text fragment |
| rectangle | java.awt.Rectangle | bounding rectangle of the recognized text fragment |

### getText() {#getText--}
```
public String getText()
```


Gets a textual content of the recognized text fragment.

**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets a bounding rectangle of the recognized text fragment.

**Returns:**
java.awt.Rectangle
