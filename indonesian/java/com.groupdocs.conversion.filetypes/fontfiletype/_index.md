---
title: "FontFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen Font."
type: docs
weight: 17
url: /id/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Mendefinisikan dokumen Font.
Mencakup tipe-tipe berikut:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
Pelajari lebih lanjut tentang format Font [di sini](../https://wiki.fileformat.com/font).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Ttf](#Ttf) | File dengan ekstensi .ttf mewakili file font yang berdasarkan teknologi font spesifikasi TrueType. |
|
|  | [Eot](#Eot) | File dengan ekstensi .eot adalah font OpenType yang disematkan dalam sebuah dokumen. |
|
|  | [Otf](#Otf) | File dengan ekstensi .otf mengacu pada format font OpenType. |
|
|  | [Cff](#Cff) | File dengan ekstensi .cff adalah Compact Font Format dan juga dikenal sebagai PostScript Type 1, atau CIDFont. |
|
|  | [Type1](#Type1) | Font Type 1 adalah teknologi Adobe yang sudah usang dan dulu banyak digunakan dalam perangkat lunak penerbitan berbasis desktop serta printer yang dapat menggunakan PostScript. |
|
|  | [Woff](#Woff) | File dengan ekstensi .woff adalah file font web yang berbasis pada Web Open Font Format (WOFF). |
|
|  | [Woff2](#Woff2) | File dengan ekstensi .woff adalah file font web yang berbasis pada Web Open Font Format (WOFF). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Konstruktor serialisasi


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


File dengan ekstensi .ttf mewakili file font yang berdasarkan teknologi font spesifikasi TrueType. Awalnya file ini dirancang dan diluncurkan oleh Apple Computer, Inc untuk Mac OS dan kemudian diadopsi oleh Microsoft untuk Windows OS. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


File dengan ekstensi .eot adalah font OpenType yang disematkan dalam sebuah dokumen. Ini biasanya digunakan dalam file web seperti halaman Web. File ini dibuat oleh Microsoft dan didukung oleh Produk Microsoft termasuk file presentasi PowerPoint .pps. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


File dengan ekstensi .otf mengacu pada format font OpenType. Format font OTF lebih skalabel dan memperluas fitur yang ada pada format TTF untuk tipografi digital. Dikembangkan oleh Microsoft dan Adobe, OTF menggabungkan fitur-fitur dari format font PostScript dan TrueType. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


File dengan ekstensi .cff adalah Compact Font Format dan juga dikenal sebagai PostScript Type 1, atau CIDFont. CFF berfungsi sebagai kontainer untuk menyimpan beberapa font bersama dalam satu unit yang disebut FontSet. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


Font Type 1 adalah teknologi Adobe yang sudah usang dan dulu banyak digunakan dalam perangkat lunak penerbitan berbasis desktop serta printer yang dapat menggunakan PostScript. Meskipun font Type 1 tidak didukung di banyak platform modern, peramban web, dan sistem operasi seluler, namun masih didukung di beberapa sistem operasi. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


File dengan ekstensi .woff adalah file font web yang berbasis pada Web Open Font Format (WOFF). Ia memiliki kontainer terkompresi khusus format yang berbasis pada jenis font TrueType (.TTF) atau OpenType (.OTT). Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


File dengan ekstensi .woff adalah file font web yang berbasis pada Web Open Font Format (WOFF). Ia memiliki kontainer terkompresi khusus format yang berbasis pada jenis font TrueType (.TTF) atau OpenType (.OTT). Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/font/woff/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Menyiapkan opsi konversi default untuk tipe file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
