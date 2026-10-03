---
title: "PersonalStorageLoadOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры загрузки документов личного хранилища."
type: docs
weight: 28
url: /ru/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Параметры загрузки документов личного хранилища.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Инициализирует новый экземпляр класса. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFolder()](#getFolder--) | Папка, которую нужно обработать. Значение по умолчанию — Inbox. |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | Установите папку, которую нужно обработать. |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} Владелец не будет преобразован |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Инициализирует новый экземпляр класса.


### getFolder() {#getFolder--}
```
public String getFolder()
```


Папка, которую нужно обработать. Значение по умолчанию — Inbox.


**Returns:**
java.lang.String - Папка, которую нужно обработать

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Установите папку, которую нужно обработать.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | папка | java.lang.String | папка |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Получает параметр, позволяющий контролировать, должен ли контейнер документов сам быть преобразован. Владелец не будет преобразован


**Returns:**
логический
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Опция для управления тем, должны ли принадлежащие документы в контейнере документов быть преобразованы


**Returns:**
логический
### getDepth() {#getDepth--}
```
public int getDepth()
```


Опция для управления тем, сколько уровней глубины использовать при выполнении преобразования


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| depth | int |  |

