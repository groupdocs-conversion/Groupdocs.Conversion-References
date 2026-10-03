---
title: "DiagramLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents de diagramme."
type: docs
weight: 15
url: /fr/java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Options de chargement des documents de diagramme.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DiagramLoadOptions()](#DiagramLoadOptions--) | Initialise une nouvelle instance de la classe [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Police par défaut pour le document Diagram. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Police par défaut pour le document Diagram. |
|
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Initialise une nouvelle instance de la classe [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions).


### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Type de fichier du document d’entrée.


**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Police par défaut pour le document Diagram. La police suivante sera utilisée si une police est manquante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Police par défaut pour le document Diagram. La police suivante sera utilisée si une police est manquante.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

