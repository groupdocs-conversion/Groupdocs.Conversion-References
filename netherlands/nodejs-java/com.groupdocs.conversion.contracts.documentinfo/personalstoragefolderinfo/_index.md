---
title: "PersonalStorageFolderInfo"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Persoonlijke opslagmapinformatie"
type: docs
weight: 33
url: /nl/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

Persoonlijke opslagmapinformatie
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [items](#items) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Naam van de map |
| [getItemsCount()](#getItemsCount--) | Aantal items in de map |
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
| [toString()](#toString--) | Stringrepresentatie van persoonlijke opslagmapinfo |
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |
| items | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


Naam van de map

**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


Aantal items in de map

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


Stringrepresentatie van persoonlijke opslagmapinfo

**Returns:**
java.lang.String - Stringrepresentatie van persoonlijke opslagmapinfo in formaat FolderName (ItemsCount)
