---
title: "RecognizedImage"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Representerar text som extraherats från en bild som resultat av dess igenkänningsprocess."
type: docs
weight: 10
url: /sv/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Representerar text, extraherad från en bild som ett resultat av dess igenkänningsprocess.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Initierar en ny instans av klassen, med hjälp av en uppsättning av igenkända rader. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [EMPTY](#EMPTY) | Tom igenkänd bild |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getLines()](#getLines--) | Hämtar textrader, med deras fragment, som igenkänts i dokumentet. |
|
|  | [getText()](#getText--) | Hämtar den textuella motsvarigheten till den strukturerade texten |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Initierar en ny instans av klassen, med hjälp av en uppsättning av igenkända rader.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | rader | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | en IEnumerable (t.ex. en lista eller en array) av igenkända rader |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Tom igenkänd bild


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Hämtar textrader, med deras fragment, som igenkänts i dokumentet.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Hämtar den textuella motsvarigheten till den strukturerade texten


**Returns:**
java.lang.String
