---
title: "PersonalStorageFolderInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Informations du dossier de stockage personnel"
type: docs
weight: 30
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

Informations du dossier de stockage personnel

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [items](#items) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Nom du dossier |
|
|  | [getItemsCount()](#getItemsCount--) | Nombre d'éléments dans le dossier |
|
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
|  | [toString()](#toString--) | Représentation sous forme de chaîne des informations du dossier de stockage personnel |
|
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |
| éléments | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


Nom du dossier


**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


Nombre d'éléments dans le dossier


**Returns:**
int
### getSubFolders() {#getSubFolders--}
```
public List<PersonalStorageFolderInfo> getSubFolders()
```




**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo>
### getItems() {#getItems--}
```
public List<PersonalStorageItemInfo> getItems()
```




**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo>
### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne des informations du dossier de stockage personnel


**Returns:**
java.lang.String - Représentation sous forme de chaîne des informations du dossier de stockage personnel au format FolderName (ItemsCount)

