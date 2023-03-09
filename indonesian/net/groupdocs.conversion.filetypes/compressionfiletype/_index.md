---
title: CompressionFileType
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Mendefinisikan format kompresi. Termasuk jenis file berikut Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . Pelajari lebih lanjut tentang format kompresiDi Sinihttps//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /id/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Mendefinisikan format kompresi. Termasuk jenis file berikut: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . Pelajari lebih lanjut tentang format kompresi[Di Sini](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Konstruktor serialisasi |

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
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 adalah file terkompresi yang dihasilkan menggunakan metode kompresi sumber terbuka BZIP2, sebagian besar pada sistem UNIX atau Linux. Ini digunakan untuk kompresi satu file dan tidak dimaksudkan untuk pengarsipan banyak file. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | File dengan ekstensi .cab milik file kabinet windows yang termasuk dalam kategori file sistem. Ini adalah file yang disimpan dalam format file arsip dalam versi Microsoft Windows yang mendukung algoritme data terkompresi, seperti LZX, Quantum, dan ZIP. Pelajari selengkapnya tentang format file ini[Di Sini](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio adalah utilitas pengarsipan file umum dan format file terkait. Ini terutama diinstal pada sistem operasi komputer mirip Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | File GZ adalah arsip terkompresi yang dibuat menggunakan algoritme kompresi gzip (GNU zip) standar. Itu mungkin berisi beberapa file terkompresi, direktori dan potongan file. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | File Gzip adalah arsip terkompresi yang dibuat menggunakan algoritme kompresi gzip (GNU zip) standar. Itu mungkin berisi beberapa file terkompresi, direktori dan potongan file. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | File dengan ekstensi .lz adalah file arsip terkompresi yang dibuat dengan Lzip, yang merupakan alat baris perintah gratis untuk kompresi. Ini mendukung penggabungan untuk mengompres file dukungan. File LZ memiliki aplikasi jenis media/lzip dan mendukung rasio kompresi yang lebih tinggi daripada BZ2. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | File dengan ekstensi .lzma adalah file arsip terkompresi yang dibuat menggunakan metode kompresi LZMA (Lempel-Ziv-Markov chain Algorithm). Ini terutama ditemukan/digunakan pada sistem operasi Unix dan mirip dengan algoritma kompresi lainnya seperti ZIP untuk meminimalkan ukuran file. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | File dengan ekstensi .rar adalah file arsip yang dibuat untuk menyimpan informasi dalam bentuk terkompresi atau normal. RAR, singkatan dari format file Roshal ARchive. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z adalah format pengarsipan untuk mengompresi file dan folder dengan rasio kompresi yang tinggi. Ini didasarkan pada arsitektur Open Source yang memungkinkan untuk menggunakan algoritma kompresi dan enkripsi apa pun. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | File dengan ekstensi .tar adalah arsip yang dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. Banyak file disimpan dalam format yang tidak terkompresi dengan dukungan penambahan file serta folder ke arsip. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ adalah format file terkompresi yang menggunakan algoritme kompresi LZMA2. Itu dirancang sebagai pengganti format gzip dan bzip2 yang populer, dan menawarkan sejumlah keuntungan dibandingkan standar lama ini. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | File AZ adalah kategori file milik file data terkompresi UNIX. File Unix terkompresi adalah jenis ekstensi file Z yang paling populer dan banyak digunakan. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | File dengan ekstensi .zip adalah arsip yang dapat menampung satu atau lebih file atau direktori. Arsip dapat menerapkan kompresi pada file yang disertakan untuk mengurangi ukuran file ZIP. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/compression/zip/) . |

### Lihat juga

* class [FileType](../filetype)
* ruang nama [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
