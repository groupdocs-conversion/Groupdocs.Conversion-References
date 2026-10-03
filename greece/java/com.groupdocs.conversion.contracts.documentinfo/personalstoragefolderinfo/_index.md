---
title: "PersonalStorageFolderInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Πληροφορίες προσωπικού φακέλου αποθήκευσης"
type: docs
weight: 30
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

Πληροφορίες προσωπικού φακέλου αποθήκευσης

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [items](#items) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Όνομα του φακέλου |
|
|  | [getItemsCount()](#getItemsCount--) | Αριθμός των στοιχείων στον φάκελο |
|
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς των πληροφοριών προσωπικού φακέλου αποθήκευσης |
|
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |
| στοιχεία | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


Όνομα του φακέλου


**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


Αριθμός των στοιχείων στον φάκελο


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


Αναπαράσταση συμβολοσειράς των πληροφοριών προσωπικού φακέλου αποθήκευσης


**Returns:**
java.lang.String - Αναπαράσταση συμβολοσειράς των πληροφοριών προσωπικού φακέλου αποθήκευσης σε μορφή FolderName (ItemsCount)

