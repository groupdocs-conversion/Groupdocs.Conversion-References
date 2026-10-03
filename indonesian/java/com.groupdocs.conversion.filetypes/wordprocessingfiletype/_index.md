---
title: "WordProcessingFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan file Pengolah Kata yang berisi informasi pengguna dalam teks biasa atau format teks kaya."
type: docs
weight: 28
url: /id/java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Mendefinisikan file Pengolahan Kata yang berisi informasi pengguna dalam format teks biasa atau format teks kaya. Format file teks biasa berisi teks yang tidak diformat dan tidak ada pengaturan font atau halaman, dll. dapat diterapkan. Sebaliknya, format file teks kaya memungkinkan opsi pemformatan seperti pengaturan jenis font, gaya (tebal, miring, bergaris bawah, dll.), margin halaman, judul, bullet dan nomor, serta beberapa fitur pemformatan lainnya.
Menyertakan jenis file berikut:
[Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Doc),
[Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docm),
[Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docx),
[Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dot),
[Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotm),
[Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotx),
[Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Odt),
[Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Ott),
[Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Rtf),
[Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Txt),
[Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Md),
Pelajari lebih lanjut tentang format Pengolahan Kata [di sini](../https://wiki.fileformat.com/word-processing).


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingFileType()](#WordProcessingFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Doc](#Doc) | File dengan ekstensi .doc mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolahan kata lainnya dalam format file biner. |
|
|  | [Docm](#Docm) | File DOCM adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau yang lebih baru dengan kemampuan menjalankan makro. |
|
|  | [Docx](#Docx) | DOCX adalah format yang terkenal untuk dokumen Microsoft Word. |
|
|  | [Dot](#Dot) | File dengan ekstensi .DOT adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk pembuatan file DOC atau DOCX selanjutnya. |
|
|  | [Dotm](#Dotm) | File dengan ekstensi DOTM mewakili file templat yang dibuat dengan Microsoft Word 2007 atau yang lebih baru. |
|
|  | [Dotx](#Dotx) | File dengan ekstensi DOTX adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk pembuatan file DOCX selanjutnya. |
|
|  | [Rtf](#Rtf) | Diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) merupakan metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi. |
|
|  | [Odt](#Odt) | File ODT adalah jenis dokumen yang dibuat dengan aplikasi pengolahan kata yang berbasis pada format File Teks OpenDocument. |
|
|  | [Ott](#Ott) | File dengan ekstensi OTT mewakili dokumen templat yang dihasilkan oleh aplikasi sesuai dengan format standar OpenDocument OASIS. |
|
|  | [Txt](#Txt) | File dengan ekstensi .TXT mewakili dokumen teks yang berisi teks biasa dalam bentuk baris. |
|
|  | [Md](#Md) | File teks yang dibuat dengan dialek bahasa Markdown disimpan dengan ekstensi file .MD atau .MARKDOWN. |
|
|  | [Ml](#Ml) | File Ml |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


Konstruktor serialisasi


### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


File dengan ekstensi .doc mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolahan kata lainnya dalam format file biner.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/doc).


### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


File DOCM adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau yang lebih baru dengan kemampuan menjalankan makro.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/docm).


### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Diperkenalkan sejak 2007 dengan rilis Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/docx).


### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


File dengan ekstensi .DOT adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk pembuatan file DOC atau DOCX selanjutnya.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/dot).


### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


File dengan ekstensi DOTM mewakili file templat yang dibuat dengan Microsoft Word 2007 atau yang lebih baru.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/dotm).


### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


File dengan ekstensi DOTX adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk pembuatan file DOCX selanjutnya.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/dotx).


### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) merupakan metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/rtf).


### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


File ODT adalah jenis dokumen yang dibuat dengan aplikasi pengolahan kata yang berbasis pada format File Teks OpenDocument.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/odt).


### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


File dengan ekstensi OTT mewakili dokumen templat yang dihasilkan oleh aplikasi sesuai dengan format standar OpenDocument OASIS.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/ott).


### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


File dengan ekstensi .TXT mewakili dokumen teks yang berisi teks biasa dalam bentuk baris.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/txt).


### Md {#Md}
```
public static final WordProcessingFileType Md
```


File teks yang dibuat dengan dialek bahasa Markdown disimpan dengan ekstensi file .MD atau .MARKDOWN. File MD disimpan dalam format teks biasa yang menggunakan bahasa Markdown yang juga mencakup simbol teks inline, mendefinisikan bagaimana teks dapat diformat seperti indentasi, pemformatan tabel, font, dan header. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/md).


### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


File Ml


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
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
