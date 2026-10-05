---
title: "DocumentInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Предоставляет базовую реализацию для получения полиморфной информации о документе"
type: docs
weight: 16
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Предоставляет базовую реализацию для получения полиморфной информации о документе
## Методы

| Метод | Описание |
| --- | --- |
| [getPropertyNames()](#getPropertyNames--) | \{@inheritDoc\} |
| [getProperty(String propertyName)](#getProperty-java.lang.String-) | \{@inheritDoc\} |
| [getPagesCount()](#getPagesCount--) | \{@inheritDoc\} |
| [getFormat()](#getFormat--) | \{@inheritDoc\} |
| [getSize()](#getSize--) | \{@inheritDoc\} |
| [getCreationDate()](#getCreationDate--) | \{@inheritDoc\} |
### getPropertyNames() {#getPropertyNames--}
```
public List<String> getPropertyNames()
```


Список всех свойств, которые можно получить для текущей информации о документе

**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Получить значение свойства, указанного ключом

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Количество страниц документа.

**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Формат документа

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Размер документа в байтах

**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Дата создания документа

**Returns:**
java.util.Date
