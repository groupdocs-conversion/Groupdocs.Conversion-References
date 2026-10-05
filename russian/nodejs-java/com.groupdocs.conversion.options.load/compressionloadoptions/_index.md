---
title: "CompressionLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов сжатия."
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/compressionloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class CompressionLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Параметры загрузки документов сжатия.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CompressionLoadOptions()](#CompressionLoadOptions--) | Инициализирует новый экземпляр класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | Владелец не будет преобразован |
| [isConvertOwned()](#isConvertOwned--) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
| [getPassword()](#getPassword--) |  |
| [setPassword(String password)](#setPassword-java.lang.String-) | Установить пароль для загрузки защищённого документа. |
| [getEqualityComponents()](#getEqualityComponents--) |  |
### CompressionLoadOptions() {#CompressionLoadOptions--}
```
public CompressionLoadOptions()
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

### getPassword() {#getPassword--}
```
public String getPassword()
```




**Returns:**
java.lang.String
### setPassword(String password) {#setPassword-java.lang.String-}
```
public void setPassword(String password)
```


Установить пароль для загрузки защищённого документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | password |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
