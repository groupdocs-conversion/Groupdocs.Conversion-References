---
title: "OlmLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Olm."
type: docs
weight: 29
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/olmloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class OlmLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Параметры загрузки документов Olm.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OlmLoadOptions()](#OlmLoadOptions--) | Инициализирует новый экземпляр класса [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions). |
## Поля

| Поле | Описание |
| --- | --- |
| [folder](#folder) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [memberwiseClone()](#memberwiseClone--) |  |
| [isConvertOwner()](#isConvertOwner--) | Владелец не будет преобразован |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getFolder()](#getFolder--) | Папка, которую нужно обработать. По умолчанию — Inbox |
| [setFolder(String folder)](#setFolder-java.lang.String-) |  |
| [getDepth()](#getDepth--) | \{@inheritDoc\} По умолчанию: 3 |
| [setDepth(int depth)](#setDepth-int-) |  |
| [deepClone()](#deepClone--) | Клонирует текущий экземпляр. |
### OlmLoadOptions() {#OlmLoadOptions--}
```
public OlmLoadOptions()
```


Инициализирует новый экземпляр класса [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions).

### folder {#folder}
```
public String folder
```


### memberwiseClone() {#memberwiseClone--}
```
public Object memberwiseClone()
```




**Returns:**
java.lang.Object
### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Владелец не будет преобразован

**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Параметр, контролирующий, должны ли принадлежащие документы в контейнере документов быть преобразованы

**Returns:**
boolean
### getFolder() {#getFolder--}
```
public String getFolder()
```


Папка, которую нужно обработать. По умолчанию — Inbox

**Returns:**
java.lang.String
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| папка | java.lang.String |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Параметр, контролирующий, на сколько уровней глубины выполнять преобразование. По умолчанию: 3

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| глубина | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонирует текущий экземпляр.

**Returns:**
java.lang.Object
