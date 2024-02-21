---
title: DocumentInfo
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Provides base implementation for retrieving polymorphic document information
type: docs
weight: 16
url: /nodejs-java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Provides base implementation for retrieving polymorphic document information
## Methods

| Method | Description |
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


List of all properties which could be get for the current document info

**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Get value for a property provided as a key

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Document pages count.

**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Document format

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Document size in bytes

**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Document creation date

**Returns:**
java.util.Date
