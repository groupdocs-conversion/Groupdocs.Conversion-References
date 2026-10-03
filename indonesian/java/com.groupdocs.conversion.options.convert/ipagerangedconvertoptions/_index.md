---
title: "IPageRangedConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili opsi konversi yang mendukung konversi daftar halaman tertentu."
type: docs
weight: 52
url: /id/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Mewakili opsi konversi yang mendukung konversi daftar halaman tertentu.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPages()](#getPages--) | Mendapatkan daftar indeks halaman yang akan dikonversi. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Mengatur daftar indeks halaman yang akan dikonversi. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Mendapatkan daftar indeks halaman yang akan dikonversi. Harus ditentukan untuk mengonversi halaman tertentu.


**Returns:**
java.util.List<java.lang.Integer> - Daftar indeks halaman yang akan dikonversi. Harus ditentukan untuk mengonversi halaman tertentu.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Mengatur daftar indeks halaman yang akan dikonversi. Harus ditentukan untuk mengonversi halaman tertentu.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | Daftar indeks halaman yang akan dikonversi. Harus ditentukan untuk mengonversi halaman tertentu. |
|

