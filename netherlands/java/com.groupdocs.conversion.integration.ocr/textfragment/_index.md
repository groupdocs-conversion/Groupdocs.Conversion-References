---
title: "TextFragment"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Stelt een deel van herkende tekst, woord, symbool enz. voor, geëxtraheerd door de OCR-engine."
type: docs
weight: 11
url: /nl/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Stelt een deel van de herkende tekst (woord, symbool, enz.) voor, geëxtraheerd door de OCR-engine.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Initialiseert een nieuw exemplaar van het herkende tekstfragment. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getText()](#getText--) | Haalt de tekstinhoud op van het herkende tekstfragment. |
|
|  | [getRectangle()](#getRectangle--) | Haalt een begrenzende rechthoek op van het herkende tekstfragment. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Initialiseert een nieuw exemplaar van het herkende tekstfragment.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | text | java.lang.String | tekstinhoud van het herkende tekstfragment |
|
|  | rechthoek | java.awt.Rectangle | begrenzende rechthoek van het herkende tekstfragment |
|

### getText() {#getText--}
```
public String getText()
```


Haalt de tekstinhoud op van het herkende tekstfragment.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Haalt een begrenzende rechthoek op van het herkende tekstfragment.


**Returns:**
[Rectangle](../../java.awt/rectangle)
