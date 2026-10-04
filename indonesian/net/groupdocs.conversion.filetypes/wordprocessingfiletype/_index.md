---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan file Pengolahan Kata yang berisi informasi pengguna dalam format teks biasa atau format teks kaya. Format file teks biasa berisi teks tidak terformat dan tidak dapat menerapkan font atau pengaturan halaman, dll. Sebaliknya, format file teks kaya memungkinkan opsi pemformatan seperti pengaturan jenis font, gaya, tebal, miring, garis bawah, dll., margin halaman, judul, bullet, dan nomor serta beberapa fitur pemformatan lainnya. Menyertakan tipe file berikut Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. Pelajari lebih lanjut tentang format Pengolahan Kata di sinihttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /id/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Mendefinisikan file Pengolahan Kata yang berisi informasi pengguna dalam format teks biasa atau format teks kaya. Format file teks biasa berisi teks tidak terformat dan tidak ada pengaturan font atau halaman, dll yang dapat diterapkan. Sebaliknya, format file teks kaya memungkinkan opsi pemformatan seperti pengaturan jenis font, gaya (tebal, miring, bergaris bawah, dll.), margin halaman, judul, bullet dan nomor, serta beberapa fitur pemformatan lainnya. Menyertakan jenis file berikut: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Pelajari lebih lanjut tentang format Pengolahan Kata [here](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Konstruktor Serialisasi |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Deskripsi tipe file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Ekstensi file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Keluarga file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Format file |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan objek lain. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Mengimplementasikan [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representasi string |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | File dengan ekstensi .doc mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolahan kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | File DOCM adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau yang lebih baru dengan kemampuan menjalankan makro. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Diperkenalkan sejak 2007 dengan rilis Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | File dengan ekstensi .DOT adalah file templat yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOC atau DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | File dengan ekstensi DOTM mewakili file templat yang dibuat dengan Microsoft Word 2007 atau yang lebih baru. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | File dengan ekstensi DOTX adalah file templat yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word adalah Office Open XML WordprocessingML yang disimpan dalam file XML datar alih-alih paket ZIP. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | File teks yang dibuat dengan dialek bahasa Markdown disimpan dengan ekstensi file .MD atau .MARKDOWN. File MD disimpan dalam format teks biasa yang menggunakan bahasa Markdown yang juga mencakup simbol teks inline, mendefinisikan cara teks dapat diformat seperti indentasi, pemformatan tabel, font, dan header. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | File ODT adalah jenis dokumen yang dibuat dengan aplikasi pengolahan kata yang berbasis pada format File Teks OpenDocument. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | File dengan ekstensi OTT mewakili dokumen templat yang dihasilkan oleh aplikasi yang mematuhi format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) merupakan metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | File dengan ekstensi .TXT mewakili dokumen teks yang berisi teks biasa dalam bentuk baris. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/word-processing/txt). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
