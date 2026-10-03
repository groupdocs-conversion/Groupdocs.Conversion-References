---
title: "DocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Menyediakan implementasi dasar untuk mengambil informasi dokumen polimorfik"
type: docs
weight: 16
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Menyediakan implementasi dasar untuk mengambil informasi dokumen polimorfik

## Metode

| Metode | Deskripsi |
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


Daftar semua properti yang dapat diambil untuk informasi dokumen saat ini


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Dapatkan nilai untuk properti yang diberikan sebagai kunci


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Jumlah halaman dokumen.


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Format dokumen


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Ukuran dokumen dalam byte


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Tanggal pembuatan dokumen


**Returns:**
java.util.Date
