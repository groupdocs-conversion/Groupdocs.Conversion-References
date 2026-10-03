---
title: "TextLine"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt Text dar, der aus einem Bild als Ergebnis seines Erkennungsprozesses extrahiert wurde."
type: docs
weight: 12
url: /de/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Stellt Text dar, der aus einem Bild als Ergebnis seines Erkennungsprozesses extrahiert wurde.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Initialisiert eine neue Instanz einer Textzeile, die vom OCR‑Engine aus einem Bild extrahiert wurde. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFragments()](#getFragments--) | Liefert ein Array von Textfragmenten, wie Symbolen und Wörtern, die in der Zeile erkannt wurden. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Initialisiert eine neue Instanz einer Textzeile, die vom OCR‑Engine aus einem Bild extrahiert wurde.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Fragmente | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | initialer Satz von Textfragmenten |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Liefert ein Array von Textfragmenten, wie Symbolen und Wörtern, die in der Zeile erkannt wurden.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
