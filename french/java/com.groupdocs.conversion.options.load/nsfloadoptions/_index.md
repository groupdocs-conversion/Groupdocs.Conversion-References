---
title: "NsfLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents NSF."
type: docs
weight: 25
url: /fr/java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Options de chargement des documents NSF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) |  |
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### NsfLoadOptions() {#NsfLoadOptions--}
```
public NsfLoadOptions()
```


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtient l'option permettant de contrôler si le conteneur du document doit être converti


**Returns:**
booléen
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option pour contrôler si les documents possédés dans le conteneur de documents doivent être convertis


**Returns:**
booléen
### getDepth() {#getDepth--}
```
public int getDepth()
```


Option pour contrôler le nombre de niveaux de profondeur à convertir


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| depth | int |  |

