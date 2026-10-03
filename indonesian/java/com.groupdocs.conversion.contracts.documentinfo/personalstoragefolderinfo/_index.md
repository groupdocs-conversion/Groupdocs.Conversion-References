---
title: "PersonalStorageFolderInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Info Folder Penyimpanan Pribadi"
type: docs
weight: 30
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

Info Folder Penyimpanan Pribadi

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [items](#items) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Nama folder |
|
|  | [getItemsCount()](#getItemsCount--) | Jumlah item dalam folder |
|
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
|  | [toString()](#toString--) | Representasi string dari info folder penyimpanan pribadi |
|
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |
| item | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


Nama folder


**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


Jumlah item dalam folder


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


Representasi string dari info folder penyimpanan pribadi


**Returns:**
java.lang.String - Representasi string dari info folder penyimpanan pribadi dalam format NamaFolder (JumlahItem)

