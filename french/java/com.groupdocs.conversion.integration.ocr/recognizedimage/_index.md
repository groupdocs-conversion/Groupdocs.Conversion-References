---
title: "RecognizedImage"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente le texte extrait d'une image à la suite de son processus de reconnaissance."
type: docs
weight: 10
url: /fr/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Représente le texte, extrait d'une image à la suite de son processus de reconnaissance.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Initialise une nouvelle instance de la classe, en utilisant un ensemble de lignes reconnues. |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [EMPTY](#EMPTY) | Image reconnue vide |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getLines()](#getLines--) | Obtient les lignes de texte, avec leurs fragments, reconnues dans le document. |
|
|  | [getText()](#getText--) | Obtient l'équivalent textuel du texte structuré |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Initialise une nouvelle instance de la classe, en utilisant un ensemble de lignes reconnues.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | lignes | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | un IEnumerable (par ex. une liste ou un tableau) de lignes reconnues |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Image reconnue vide


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Obtient les lignes de texte, avec leurs fragments, reconnues dans le document.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Obtient l'équivalent textuel du texte structuré


**Returns:**
java.lang.String
