---
title: "TextLine"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Representerar text som extraherats från en bild som resultat av dess igenkänningsprocess."
type: docs
weight: 12
url: /sv/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Representerar text, extraherad från en bild som ett resultat av dess igenkänningsprocess.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Initierar en ny instans av en textrad, extraherad av OCR-motorn från en bild. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFragments()](#getFragments--) | Hämtar en array av textfragment, såsom symboler och ord, som igenkänts i raden. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Initierar en ny instans av en textrad, extraherad av OCR-motorn från en bild.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fragment | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | initial uppsättning av textfragment |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Hämtar en array av textfragment, såsom symboler och ord, som igenkänts i raden.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
