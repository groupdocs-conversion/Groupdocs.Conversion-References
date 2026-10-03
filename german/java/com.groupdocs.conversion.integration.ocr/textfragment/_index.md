---
title: "TextFragment"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt einen Teil des erkannten Textes, Wort, Symbol usw. dar, das vom OCR‑Engine extrahiert wurde."
type: docs
weight: 11
url: /de/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Stellt einen Teil des erkannten Textes (Wort, Symbol usw.) dar, der von der OCR-Engine extrahiert wurde.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Initialisiert eine neue Instanz des erkannten Textfragments. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Liefert den Textinhalt des erkannten Textfragments. |
|
|  | [getRectangle()](#getRectangle--) | Liefert das Begrenzungsrechteck des erkannten Textfragments. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Initialisiert eine neue Instanz des erkannten Textfragments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Textinhalt des erkannten Textfragments |
|
|  | Rechteck | java.awt.Rectangle | Begrenzungsrechteck des erkannten Textfragments |
|

### getText() {#getText--}
```
public String getText()
```


Liefert den Textinhalt des erkannten Textfragments.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Liefert das Begrenzungsrechteck des erkannten Textfragments.


**Returns:**
[Rectangle](../../java.awt/rectangle)
