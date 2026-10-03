---
title: "IPageSizeConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili opsi konversi yang mendukung ukuran halaman."
type: docs
weight: 54
url: /id/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Mewakili opsi konversi yang mendukung ukuran halaman.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Mendapatkan ukuran halaman yang diinginkan setelah konversi |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Mengatur ukuran halaman yang diinginkan setelah konversi |
|
|  | [getPageWidth()](#getPageWidth--) | Lebar halaman yang ditentukan dalam poin jika diatur ke PageSize.Custom |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | Mengatur lebar halaman yang diinginkan |
|
|  | [getPageHeight()](#getPageHeight--) | Tinggi halaman yang ditentukan dalam poin jika diatur ke PageSize.Custom |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | Mengatur tinggi halaman yang diinginkan |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Mendapatkan ukuran halaman yang diinginkan setelah konversi


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Mengatur ukuran halaman yang diinginkan setelah konversi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Lebar halaman yang ditentukan dalam poin jika diatur ke PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Mengatur lebar halaman yang diinginkan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Tinggi halaman yang ditentukan dalam poin jika diatur ke PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Mengatur tinggi halaman yang diinginkan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageHeight | float |  |

