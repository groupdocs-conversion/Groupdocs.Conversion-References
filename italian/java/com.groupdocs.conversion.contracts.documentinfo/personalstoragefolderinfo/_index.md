---
title: "PersonalStorageFolderInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Informazioni sulla cartella Personal Storage Folder"
type: docs
weight: 30
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

Informazioni sulla cartella Personal Storage Folder

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [items](#items) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Nome della cartella |
|
|  | [getItemsCount()](#getItemsCount--) | Conteggio degli elementi nella cartella |
|
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
|  | [toString()](#toString--) | Rappresentazione stringa delle informazioni della cartella di archiviazione personale |
|
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |
| elementi | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


Nome della cartella


**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


Conteggio degli elementi nella cartella


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


Rappresentazione stringa delle informazioni della cartella di archiviazione personale


**Returns:**
java.lang.String - Rappresentazione stringa delle informazioni della cartella di archiviazione personale nel formato NomeCartella (ConteggioElementi)

