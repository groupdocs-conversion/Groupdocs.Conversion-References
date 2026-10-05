---
title: "MboxLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Mbox."
type: docs
weight: 26
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Параметры загрузки документов Mbox.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MboxLoadOptions()](#MboxLoadOptions--) | Инициализирует новый экземпляр класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | Владелец не будет преобразован |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getDepth()](#getDepth--) | \{@inheritDoc\} По умолчанию: 3 |
| [setDepth(int depth)](#setDepth-int-) | \{@inheritDoc\} |
| [getEqualityComponents()](#getEqualityComponents--) | \{@inheritDoc\} |
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


Инициализирует новый экземпляр класса.

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

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
