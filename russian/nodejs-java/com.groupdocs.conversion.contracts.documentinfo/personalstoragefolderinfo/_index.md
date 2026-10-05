---
title: "PersonalStorageFolderInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Информация о папке Personal Storage"
type: docs
weight: 33
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

Информация о папке Personal Storage
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [items](#items) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Имя папки |
| [getItemsCount()](#getItemsCount--) | Количество элементов в папке |
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
| [toString()](#toString--) | Строковое представление информации о папке личного хранилища |
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |
| элементы | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


Имя папки

**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


Количество элементов в папке

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


Строковое представление информации о папке личного хранилища

**Returns:**
java.lang.String - Строковое представление информации о папке личного хранилища в формате FolderName (ItemsCount)
