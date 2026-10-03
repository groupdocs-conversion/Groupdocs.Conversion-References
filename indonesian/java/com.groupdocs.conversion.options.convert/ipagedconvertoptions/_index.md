---
title: "IPagedConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili opsi konversi yang memungkinkan pembatasan halaman dengan menentukan halaman mulai dan jumlah halaman."
type: docs
weight: 55
url: /id/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Mewakili opsi konversi yang memungkinkan pembatasan halaman dengan menentukan halaman mulai dan jumlah halaman.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Mendapatkan nomor halaman untuk memulai konversi. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Mengatur nomor halaman untuk memulai konversi. |
|
|  | [getPagesCount()](#getPagesCount--) | Mendapatkan jumlah halaman yang akan dikonversi mulai dari PageNumber. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | Mengatur jumlah halaman yang akan dikonversi mulai dari PageNumber. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Mendapatkan nomor halaman untuk memulai konversi.


**Returns:**
java.lang.Integer - Nomor halaman untuk memulai konversi.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Mengatur nomor halaman untuk memulai konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageNumber | int | Nomor halaman untuk memulai konversi. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Mendapatkan jumlah halaman yang akan dikonversi mulai dari PageNumber.


**Returns:**
java.lang.Integer - Jumlah halaman yang akan dikonversi mulai dari PageNumber.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Mengatur jumlah halaman yang akan dikonversi mulai dari PageNumber.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pagesCount | int | Jumlah halaman yang akan dikonversi mulai dari PageNumber. |
|

