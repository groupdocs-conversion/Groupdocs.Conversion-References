---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan format kompresi. Mencakup tipe file berikut Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. Pelajari lebih lanjut tentang format kompresi di sini https//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /id/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Mendefinisikan format kompresi. Mencakup tipe file berikut: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). Pelajari lebih lanjut tentang format kompresi [di sini](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Deskripsi tipe file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Ekstensi file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Keluarga file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Format file |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Mendefinisikan apakah format mendukung beberapa file/folder dalam satu arsip. |

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
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | File dengan ekstensi .aar adalah Apple Archive, wadah yang disertakan Apple dengan macOS untuk mengelompokkan file dan folder. Setiap entri dikompresi secara terpisah, biasanya dengan LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | File dengan ekstensi .alz adalah arsip ALZip, format dari ESTsoft yang banyak digunakan di Korea Selatan. Entri dapat dienkripsi secara individual dengan kata sandi. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 adalah file terkompresi yang dihasilkan menggunakan metode kompresi sumber terbuka BZIP2, biasanya pada sistem UNIX atau Linux. Ini digunakan untuk mengompresi satu file dan tidak dimaksudkan untuk mengarsipkan banyak file. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | File dengan ekstensi .cab adalah file kabinet Windows yang termasuk dalam kategori file sistem. Ini adalah file yang disimpan dalam format arsip pada versi Microsoft Windows yang mendukung algoritma data terkompresi, seperti LZX, Quantum, dan ZIP. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio adalah utilitas pengarsip file umum dan format file terkait. Ini terutama diinstal pada sistem operasi komputer mirip Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | File GZ adalah arsip terkompresi yang dibuat menggunakan algoritma kompresi standar gzip (GNU zip). Itu dapat berisi beberapa file terkompresi, direktori, dan stub file. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | File Gzip adalah arsip terkompresi yang dibuat menggunakan algoritma kompresi standar gzip (GNU zip). Itu dapat berisi beberapa file terkompresi, direktori, dan stub file. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | File dengan ekstensi .iso adalah file gambar disk arsip yang tidak terkompresi yang mewakili isi seluruh data pada disc optik seperti CD atau DVD. Berdasarkan standar ISO-9660, format file gambar ISO berisi data disc bersama dengan informasi sistem file yang disimpan di dalamnya. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | File dengan ekstensi .lzh dan .lha biasanya terkait dengan format file kompresi arsip. Format file ini sama dengan format kompresi file lainnya seperti ZIP, RAR, dll. Tujuan utama format-format ini adalah mengurangi ukuran file agar mudah dikirim serta menyimpannya bersama dalam bentuk terkompresi. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | File dengan ekstensi .lz adalah file arsip terkompresi yang dibuat dengan Lzip, sebuah alat baris perintah gratis untuk kompresi. Ia mendukung penggabungan untuk mengompresi file pendukung. File LZ memiliki tipe media application/lzip dan mendukung rasio kompresi yang lebih tinggi dibandingkan BZ2. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | File dengan ekstensi .lz4 adalah file arsip terkompresi yang dibuat dengan aplikasi/utility yang mendukung kompresi LZ4. Algoritma LZ4 berfokus pada kompromi antara kecepatan dan rasio kompresi. Arsip LZ4 yang terkompresi dapat dibuat menggunakan utilitas baris perintah LZ4 dan dapat didekompresi dengan utilitas yang sama. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | File dengan ekstensi .lzma adalah file arsip terkompresi yang dibuat menggunakan metode kompresi LZMA (Lempel-Ziv-Markov chain Algorithm). File ini biasanya ditemukan/ digunakan pada sistem operasi Unix dan mirip dengan algoritma kompresi lainnya seperti ZIP untuk meminimalkan ukuran file. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | File dengan ekstensi .rar adalah file arsip yang dibuat untuk menyimpan informasi dalam bentuk terkompresi atau normal. RAR, yang merupakan singkatan dari Roshal ARchive file format. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z adalah format arsip untuk mengompresi file dan folder dengan rasio kompresi tinggi. Format ini berbasis arsitektur Open Source yang memungkinkan penggunaan berbagai algoritma kompresi dan enkripsi. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | File dengan ekstensi .tar adalah arsip yang dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. Beberapa file disimpan dalam format tidak terkompresi dengan dukungan penambahan file maupun folder ke dalam arsip. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Arsip uuencoded adalah file atau kumpulan file yang telah dienkode menggunakan skema pengkodean Unix-to-Unix (uuencode). Metode pengkodean ini mengubah data biner menjadi format teks, sehingga lebih mudah mengirim file melalui saluran yang hanya mendukung teks, seperti email. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | File dengan ekstensi .wim adalah arsip Windows Imaging Format, sebuah gambar disk berbasis file yang digunakan Microsoft untuk menyebarkan Windows. Sebuah arsip tunggal menyimpan satu atau lebih image dan menyimpan setiap file hanya sekali, terlepas dari berapa banyak image yang merujuknya. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | File dengan ekstensi .xar adalah eXtensible ARchive, sebuah format yang dibangun di sekitar tabel isi yang disimpan sebagai XML terkompresi. Format ini digunakan untuk mendistribusikan paket instalasi macOS dan menyimpan setiap entri terkompresi secara terpisah. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ adalah format file terkompresi yang menggunakan algoritma kompresi LZMA2. Format ini dirancang sebagai pengganti format gzip dan bzip2 yang populer, dan menawarkan sejumlah keunggulan dibandingkan standar lama tersebut. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | File Z adalah kategori file yang termasuk dalam file data terkompresi UNIX. File Unix terkompresi adalah jenis ekstensi Z yang paling populer dan banyak digunakan. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | File dengan ekstensi .zip adalah arsip yang dapat menyimpan satu atau lebih file atau direktori. Arsip dapat diberi kompresi pada file yang termasuk untuk mengurangi ukuran file ZIP. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | File ZST adalah file terkompresi yang dihasilkan dengan algoritma kompresi Zstandard (zstd). Ini adalah file terkompresi yang dibuat dengan kompresi lossless oleh algoritma tersebut. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/zst/). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
