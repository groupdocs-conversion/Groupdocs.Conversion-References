---
title: WordProcessingFileType
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Menentukan file Pemrosesan Kata yang berisi informasi pengguna dalam format teks biasa atau teks kaya. Format file teks biasa berisi teks yang tidak diformat dan tidak ada pengaturan font atau halaman dll yang dapat diterapkan. Sebaliknya format file teks kaya memungkinkan opsi pemformatan seperti mengatur jenis font gaya tebal miring garis bawah dll. margin halaman judul poin dan angka dan beberapa fitur pemformatan lainnya. Termasuk jenis file berikut Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log . Pelajari lebih lanjut tentang format Pemrosesan KataDi Sinihttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 1090
url: /id/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Menentukan file Pemrosesan Kata yang berisi informasi pengguna dalam format teks biasa atau teks kaya. Format file teks biasa berisi teks yang tidak diformat dan tidak ada pengaturan font atau halaman dll yang dapat diterapkan. Sebaliknya, format file teks kaya memungkinkan opsi pemformatan seperti mengatur jenis font, gaya (tebal, miring, garis bawah, dll.), margin halaman, judul, poin dan angka, dan beberapa fitur pemformatan lainnya. Termasuk jenis file berikut: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , Mobi , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . Log . Pelajari lebih lanjut tentang format Pemrosesan Kata[Di Sini](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Konstruktor serialisasi |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Deskripsi jenis file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Ekstensi file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Keluarga file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Format file |

## Metode

| Nama | Keterangan |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan yang lain. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Menentukan apakah dua instance objek sama. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representasi string |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | File dengan ekstensi .doc mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolah kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | File DOCM adalah dokumen yang dibuat Microsoft Word 2007 atau lebih tinggi dengan kemampuan untuk menjalankan makro. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX adalah format terkenal untuk dokumen Microsoft Word. Diperkenalkan dari tahun 2007 dengan dirilisnya Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | File dengan ekstensi .DOT adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOC atau DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | File dengan ekstensi DOTM mewakili file template yang dibuat dengan Microsoft Word 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | File dengan ekstensi DOTX adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | File teks yang dibuat dengan dialek bahasa Markdown disimpan dengan ekstensi file .MD atau .MARKDOWN. File MD disimpan dalam format teks biasa yang menggunakan bahasa Markdown yang juga menyertakan simbol teks sebaris, yang menentukan bagaimana teks dapat diformat seperti indentasi, pemformatan tabel, font, dan header. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | File ODT adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang didasarkan pada format File Teks OpenDocument. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | File dengan ekstensi OTT mewakili dokumen template yang dibuat oleh aplikasi sesuai dengan format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) mewakili metode pengkodean teks dan grafik yang diformat untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | File dengan ekstensi .TXT mewakili dokumen teks yang berisi teks biasa dalam bentuk garis. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/txt) . |

### Lihat juga

* class [FileType](../filetype)
* ruang nama [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
