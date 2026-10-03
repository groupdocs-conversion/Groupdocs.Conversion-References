---
title: "TextFragment"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente une partie du texte reconnu, mot, symbole, etc., extrait par le moteur OCR."
type: docs
weight: 11
url: /fr/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Représente une partie du texte reconnu (mot, symbole, etc.), extraite par le moteur OCR.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Initialise une nouvelle instance du fragment de texte reconnu. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getText()](#getText--) | Obtient le contenu textuel du fragment de texte reconnu. |
|
|  | [getRectangle()](#getRectangle--) | Obtient le rectangle englobant du fragment de texte reconnu. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Initialise une nouvelle instance du fragment de texte reconnu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | contenu textuel du fragment de texte reconnu |
|
|  | rectangle | java.awt.Rectangle | rectangle englobant du fragment de texte reconnu |
|

### getText() {#getText--}
```
public String getText()
```


Obtient le contenu textuel du fragment de texte reconnu.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Obtient le rectangle englobant du fragment de texte reconnu.


**Returns:**
[Rectangle](../../java.awt/rectangle)
