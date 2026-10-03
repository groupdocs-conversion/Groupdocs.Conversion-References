---
title: "TextLine"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Stelt tekst voor die uit een afbeelding is gehaald als resultaat van het herkenningsproces."
type: docs
weight: 12
url: /nl/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Stelt tekst voor, geëxtraheerd uit een afbeelding als resultaat van het herkenningsproces.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Initialiseert een nieuw exemplaar van een tekstregel, geëxtraheerd door de OCR-engine uit een afbeelding. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFragments()](#getFragments--) | Haalt een array op van tekstfragmenten, zoals symbolen en woorden, die in de regel zijn herkend. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Initialiseert een nieuw exemplaar van een tekstregel, geëxtraheerd door de OCR-engine uit een afbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fragmenten | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | initiële set van tekstfragmenten |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Haalt een array op van tekstfragmenten, zoals symbolen en woorden, die in de regel zijn herkend.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
