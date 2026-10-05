---
title: "PersonalStorageFolderInfo"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Kişisel Depolama Klasör Bilgisi"
type: docs
weight: 33
url: /tr/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

Kişisel Depolama Klasör Bilgisi
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [items](#items) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Klasörün adı |
| [getItemsCount()](#getItemsCount--) | Klasördeki öğelerin sayısı |
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
| [toString()](#toString--) | Kişisel depolama klasörü bilgisinin dize temsili |
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |
| öğeler | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


Klasörün adı

**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


Klasördeki öğelerin sayısı

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


Kişisel depolama klasörü bilgisinin dize temsili

**Returns:**
java.lang.String - Kişisel depolama klasörü bilgisinin FolderName (ItemsCount) biçimindeki dize temsili
