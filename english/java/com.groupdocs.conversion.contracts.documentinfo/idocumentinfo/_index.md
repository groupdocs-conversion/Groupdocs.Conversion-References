---
title: IDocumentInfo
second_title: GroupDocs.Conversion for Java API Reference
description: Contains metadata for a document.
type: docs
weight: 49
url: /java/com.groupdocs.conversion.contracts.documentinfo/idocumentinfo/
---```
public interface IDocumentInfo
```

Contains metadata for a document.
## Methods

| Method | Description |
| --- | --- |
| [getPagesCount()](#getPagesCount--) | Document pages count. |
| [getFormat()](#getFormat--) | Document format |
| [getSize()](#getSize--) | Document size in bytes |
| [getCreationDate()](#getCreationDate--) | Document creation date |
| [getPropertyNames()](#getPropertyNames--) | List of all properties which could be get for the current document info |
| [getProperty(String propertyName)](#getProperty-java.lang.String-) | Get value for a property provided as a key |
### getPagesCount() {#getPagesCount--}
```
public abstract int getPagesCount()
```


Document pages count.

**Returns:**
int
### getFormat() {#getFormat--}
```
public abstract String getFormat()
```


Document format

**Returns:**
java.lang.String - Document format
### getSize() {#getSize--}
```
public abstract long getSize()
```


Document size in bytes

**Returns:**
long - Document size in bytes
### getCreationDate() {#getCreationDate--}
```
public abstract Date getCreationDate()
```


Document creation date

**Returns:**
java.util.Date - Document creation date
### getPropertyNames() {#getPropertyNames--}
```
public abstract List<String> getPropertyNames()
```


List of all properties which could be get for the current document info

**Returns:**
java.util.List<java.lang.String> - List of all properties which could be get for the current document info
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public abstract String getProperty(String propertyName)
```


Get value for a property provided as a key

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | property name |

**Returns:**
java.lang.String - value for a property provided as a key
