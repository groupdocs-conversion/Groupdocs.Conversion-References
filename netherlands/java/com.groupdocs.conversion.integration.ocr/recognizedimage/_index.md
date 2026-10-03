---
title: "RecognizedImage"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Stelt tekst voor die uit een afbeelding is gehaald als resultaat van het herkenningsproces."
type: docs
weight: 10
url: /nl/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Stelt tekst voor, geëxtraheerd uit een afbeelding als resultaat van het herkenningsproces.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Initialiseert een nieuw exemplaar van de klasse, met gebruik van een set van herkende regels. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [EMPTY](#EMPTY) | Lege herkende afbeelding |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getLines()](#getLines--) | Haalt tekstregels op, met hun fragmenten, die binnen het document zijn herkend. |
|
|  | [getText()](#getText--) | Haalt de tekstuele equivalent op van de gestructureerde tekst |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Initialiseert een nieuw exemplaar van de klasse, met gebruik van een set van herkende regels.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | regels | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | een IEnumerable (bijv. een lijst of een array) van herkende regels |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Lege herkende afbeelding


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Haalt tekstregels op, met hun fragmenten, die binnen het document zijn herkend.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Haalt de tekstuele equivalent op van de gestructureerde tekst


**Returns:**
java.lang.String
