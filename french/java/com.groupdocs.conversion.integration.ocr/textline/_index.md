---
title: "TextLine"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente le texte extrait d'une image à la suite de son processus de reconnaissance."
type: docs
weight: 12
url: /fr/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Représente le texte, extrait d'une image à la suite de son processus de reconnaissance.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Initialise une nouvelle instance d'une ligne de texte, extraite par le moteur OCR d'une image. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFragments()](#getFragments--) | Obtient un tableau de fragments de texte, tels que des symboles et des mots, reconnus dans la ligne. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Initialise une nouvelle instance d'une ligne de texte, extraite par le moteur OCR d'une image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fragments | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | ensemble initial de fragments de texte |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Obtient un tableau de fragments de texte, tels que des symboles et des mots, reconnus dans la ligne.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
