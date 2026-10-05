---
title: "OlmFolderInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Информация о папке Olm"
type: docs
weight: 28
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/olmfolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class OlmFolderInfo extends ValueObject
```

Информация о папке Olm
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OlmFolderInfo(String name, int count)](#OlmFolderInfo-java.lang.String-int-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Имя папки |
| [getItemsCount()](#getItemsCount--) | Количество элементов в папке |
| [toString()](#toString--) | Строковое представление информации о папке личного хранилища Строковое представление информации о папке личного хранилища в формате FolderName (ItemsCount) |
### OlmFolderInfo(String name, int count) {#OlmFolderInfo-java.lang.String-int-}
```
public OlmFolderInfo(String name, int count)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |
| количество | int |  |

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
### toString() {#toString--}
```
public String toString()
```


Строковое представление информации о папке личного хранилища Строковое представление информации о папке личного хранилища в формате FolderName (ItemsCount)

**Returns:**
java.lang.String
