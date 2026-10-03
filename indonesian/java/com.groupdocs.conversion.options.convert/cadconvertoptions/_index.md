---
title: "CadConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk konversi ke tipe Cad."
type: docs
weight: 10
url: /id/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Opsi untuk konversi ke tipe Cad.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [CadConvertOptions()](#CadConvertOptions--) | Menginisialisasi instance baru dari kelas. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Menginisialisasi instance baru dari kelas.


### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Mendapatkan nomor halaman untuk memulai konversi.


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Mengatur nomor halaman untuk memulai konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Mendapatkan jumlah halaman yang akan dikonversi mulai dari PageNumber.


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Mengatur jumlah halaman yang akan dikonversi mulai dari PageNumber.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pagesCount | int |  |

