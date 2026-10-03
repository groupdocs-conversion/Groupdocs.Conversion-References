---
title: "NsfLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen Nsf."
type: docs
weight: 25
url: /id/java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opsi untuk memuat dokumen Nsf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) |  |
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
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


Mendapatkan opsi untuk mengontrol apakah kontainer dokumen itu sendiri harus dikonversi


**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opsi untuk mengontrol apakah dokumen yang dimiliki dalam kontainer dokumen harus dikonversi


**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```


Opsi untuk mengontrol berapa banyak tingkat kedalaman untuk melakukan konversi


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| depth | int |  |

