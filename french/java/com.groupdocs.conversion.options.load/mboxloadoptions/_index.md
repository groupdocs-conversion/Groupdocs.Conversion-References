---
title: "MboxLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents Mbox."
type: docs
weight: 23
url: /fr/java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Options de chargement des documents Mbox.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [MboxLoadOptions()](#MboxLoadOptions--) | Initialise une nouvelle instance de la classe. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isConvertOwner()](#isConvertOwner--) | Le propriétaire ne sera pas converti |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} Par défaut: 3 |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | {@inheritDoc} |
|
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


Initialise une nouvelle instance de la classe.


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Le propriétaire ne sera pas converti


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


Option pour contrôler le nombre de niveaux de profondeur à effectuer lors de la conversion. Par défaut: 3


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

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
