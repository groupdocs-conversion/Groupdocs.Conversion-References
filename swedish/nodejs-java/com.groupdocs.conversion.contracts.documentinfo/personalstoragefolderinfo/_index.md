---
title: "PersonalStorageFolderInfo"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Personal Storage-mappinformation"
type: docs
weight: 33
url: /sv/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

Personal Storage-mappinformation
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [items](#items) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Namn på mappen |
| [getItemsCount()](#getItemsCount--) | Antal objekt i mappen |
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
| [toString()](#toString--) | Strängrepresentation av personlig lagringsmappinformation |
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| objekt | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


Namn på mappen

**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


Antal objekt i mappen

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


Strängrepresentation av personlig lagringsmappinformation

**Returns:**
java.lang.String - Strängrepresentation av personlig lagringsmappinformation i formatet FolderName (ItemsCount)
