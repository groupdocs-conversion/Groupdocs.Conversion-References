---
title: "DocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "提供用于检索多态文档信息的基础实现"
type: docs
weight: 16
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

提供用于检索多态文档信息的基础实现

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPropertyNames()](#getPropertyNames--) | {@inheritDoc} |
|
|  | [getProperty(String propertyName)](#getProperty-java.lang.String-) | {@inheritDoc} |
|
|  | [getPagesCount()](#getPagesCount--) | {@inheritDoc} |
|
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [getSize()](#getSize--) | {@inheritDoc} |
|
|  | [getCreationDate()](#getCreationDate--) | {@inheritDoc} |
|
### getPropertyNames() {#getPropertyNames--}
```
public List<String> getPropertyNames()
```


当前文档信息可获取的所有属性列表


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


根据键获取属性的值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


文档页数。


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


文档格式


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


文档大小（字节）


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


文档创建日期


**Returns:**
java.util.Date
