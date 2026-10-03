---
title: "DocumentInfo"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Polimorfik belge bilgilerini almak için temel uygulama sağlar"
type: docs
weight: 16
url: /tr/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Polimorfik belge bilgilerini almak için temel uygulama sağlar

## Yöntemler

| Yöntem | Açıklama |
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


Mevcut belge bilgisi için alınabilecek tüm özelliklerin listesi


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Anahtar olarak sağlanan bir özelliğin değerini al


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Belge sayfa sayısı.


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Belge formatı


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Belge boyutu bayt cinsinden


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Belge oluşturma tarihi


**Returns:**
java.util.Date
