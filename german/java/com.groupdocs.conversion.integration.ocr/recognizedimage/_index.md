---
title: "RecognizedImage"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt Text dar, der aus einem Bild als Ergebnis seines Erkennungsprozesses extrahiert wurde."
type: docs
weight: 10
url: /de/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Stellt Text dar, der aus einem Bild als Ergebnis seines Erkennungsprozesses extrahiert wurde.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Initialisiert eine neue Instanz der Klasse und verwendet dabei einen Satz erkannter Zeilen. |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [EMPTY](#EMPTY) | Leeres erkanntes Bild |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getLines()](#getLines--) | Liefert Textzeilen mit ihren Fragmenten, die im Dokument erkannt wurden. |
|
|  | [getText()](#getText--) | Liefert das textuelle Äquivalent des strukturierten Textes |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Initialisiert eine neue Instanz der Klasse und verwendet dabei einen Satz erkannter Zeilen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Zeilen | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | ein IEnumerable (z. B. eine Liste oder ein Array) erkannter Zeilen |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Leeres erkanntes Bild


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Liefert Textzeilen mit ihren Fragmenten, die im Dokument erkannt wurden.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Liefert das textuelle Äquivalent des strukturierten Textes


**Returns:**
java.lang.String
