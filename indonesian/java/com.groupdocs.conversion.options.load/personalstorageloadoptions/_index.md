---
title: "PersonalStorageLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen penyimpanan pribadi."
type: docs
weight: 28
url: /id/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opsi untuk memuat dokumen penyimpanan pribadi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Menginisialisasi instance baru dari kelas. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFolder()](#getFolder--) | Folder yang akan diproses Nilai default adalah Inbox |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | Atur folder yang akan diproses |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} Pemilik tidak akan dikonversi |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Menginisialisasi instance baru dari kelas.


### getFolder() {#getFolder--}
```
public String getFolder()
```


Folder yang akan diproses Nilai default adalah Inbox


**Returns:**
java.lang.String - Folder yang akan diproses

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Atur folder yang akan diproses


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | folder | java.lang.String | folder |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Mendapatkan opsi untuk mengontrol apakah kontainer dokumen itu sendiri harus dikonversi Pemilik tidak akan dikonversi


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

