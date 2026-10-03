---
title: "PersonalStorageFolderInfo"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Información de la carpeta de almacenamiento personal"
type: docs
weight: 30
url: /es/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

Información de la carpeta de almacenamiento personal

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [items](#items) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Nombre de la carpeta |
|
|  | [getItemsCount()](#getItemsCount--) | Cantidad de elementos en la carpeta |
|
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
|  | [toString()](#toString--) | Representación en cadena de la información de la carpeta de almacenamiento personal |
|
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |
| elementos | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


Nombre de la carpeta


**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


Cantidad de elementos en la carpeta


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


Representación en cadena de la información de la carpeta de almacenamiento personal


**Returns:**
java.lang.String - Representación en cadena de la información de la carpeta de almacenamiento personal en formato NombreCarpeta (CantidadElementos)

