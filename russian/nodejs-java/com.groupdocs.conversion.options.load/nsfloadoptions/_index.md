---
title: "NsfLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Nsf."
type: docs
weight: 28
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Параметры загрузки документов Nsf.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) |  |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### NsfLoadOptions() {#NsfLoadOptions--}
```
public NsfLoadOptions()
```


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Получает опцию, контролирующую, должен ли контейнер документов быть преобразован

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


Параметр, позволяющий контролировать, на сколько уровней глубины выполнять преобразование

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

