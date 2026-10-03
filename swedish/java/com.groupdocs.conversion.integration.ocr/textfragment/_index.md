---
title: "TextFragment"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Representerar en del av igenkänd text, ord, symbol etc extraherad av OCR-motorn."
type: docs
weight: 11
url: /sv/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Representerar en del av igenkänd text (ord, symbol osv.), extraherad av OCR-motorn.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Initierar en ny instans av det igenkända textfragmentet. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getText()](#getText--) | Hämtar det textuella innehållet i det igenkända textfragmentet. |
|
|  | [getRectangle()](#getRectangle--) | Hämtar en omgivande rektangel för det igenkända textfragmentet. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Initierar en ny instans av det igenkända textfragmentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | textuellt innehåll i det igenkända textfragmentet |
|
|  | rektangel | java.awt.Rectangle | omslutande rektangel för det igenkända textfragmentet |
|

### getText() {#getText--}
```
public String getText()
```


Hämtar det textuella innehållet i det igenkända textfragmentet.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Hämtar en omgivande rektangel för det igenkända textfragmentet.


**Returns:**
[Rectangle](../../java.awt/rectangle)
