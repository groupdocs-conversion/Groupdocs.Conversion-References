---
title: "PersonalStorageLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents de stockage personnel."
type: docs
weight: 28
url: /fr/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Options de chargement des documents de stockage personnel.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Initialise une nouvelle instance de la classe. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFolder()](#getFolder--) | Dossier à traiter La valeur par défaut est Boîte de réception |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | Définir le dossier à traiter |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} Le propriétaire ne sera pas converti |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Initialise une nouvelle instance de la classe.


### getFolder() {#getFolder--}
```
public String getFolder()
```


Dossier à traiter La valeur par défaut est Boîte de réception


**Returns:**
java.lang.String - Dossier à traiter

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Définir le dossier à traiter


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | dossier | java.lang.String | dossier |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtient l'option permettant de contrôler si le conteneur de documents lui-même doit être converti Le propriétaire ne sera pas converti


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

