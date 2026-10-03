---
title: "WordProcessingBookmarksOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour la gestion des signets dans WordProcessing"
type: docs
weight: 39
url: /fr/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Options pour la gestion des signets dans WordProcessing

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Spécifie le niveau par défaut dans le plan du document où afficher les signets Word. |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Spécifie le niveau par défaut dans le plan du document où afficher les signets Word. |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Spécifie le nombre de niveaux de titres (paragraphes formatés avec les styles de titre) à inclure dans le plan du document. |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Spécifie le nombre de niveaux de titres (paragraphes formatés avec les styles de titre) à inclure dans le plan du document. |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Spécifie le nombre de niveaux du plan du document à afficher développés lorsque le fichier est visualisé. |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Spécifie le nombre de niveaux du plan du document à afficher développés lorsque le fichier est visualisé. |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Spécifie le niveau par défaut dans le plan du document où afficher les signets Word. La valeur par défaut est 0. La plage valide est de 0 à 9.


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Spécifie le niveau par défaut dans le plan du document où afficher les signets Word. La valeur par défaut est 0. La plage valide est de 0 à 9.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Spécifie le nombre de niveaux de titres (paragraphes formatés avec les styles de titre) à inclure dans le plan du document. La valeur par défaut est 0. La plage valide est de 0 à 9.


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Spécifie le nombre de niveaux de titres (paragraphes formatés avec les styles de titre) à inclure dans le plan du document. La valeur par défaut est 0. La plage valide est de 0 à 9.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Spécifie le nombre de niveaux du plan du document à afficher développés lorsque le fichier est visualisé. La valeur par défaut est 0. La plage valide est de 0 à 9. Notez que cette option ne fonctionnera pas lors de l'enregistrement au format XPS.


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Spécifie le nombre de niveaux du plan du document à afficher développés lorsque le fichier est visualisé. La valeur par défaut est 0. La plage valide est de 0 à 9. Notez que cette option ne fonctionnera pas lors de l'enregistrement au format XPS.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

