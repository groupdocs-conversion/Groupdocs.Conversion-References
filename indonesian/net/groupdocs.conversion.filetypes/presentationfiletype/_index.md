---
title: PresentationFileType
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Menentukan format file Presentasi yang menyimpan kumpulan rekaman untuk mengakomodasi data presentasi seperti slide bentuk teks animasi video audio dan objek tersemat. Termasuk jenis file berikut Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . Pelajari lebih lanjut tentang format PresentasiDi Sinihttps//wiki.fileformat.com/presentation .
type: docs
weight: 1020
url: /id/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Menentukan format file Presentasi yang menyimpan kumpulan rekaman untuk mengakomodasi data presentasi seperti slide, bentuk, teks, animasi, video, audio, dan objek tersemat. Termasuk jenis file berikut: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . Pelajari lebih lanjut tentang format Presentasi[Di Sini](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Konstruktor serialisasi |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | File dengan ekstensi FODP mewakili OpenDocument Flat XML Presentation. File presentasi disimpan dalam format OpenDocument, tetapi disimpan menggunakan format XML datar alih-alih wadah .ZIP yang digunakan oleh file .ODP standar |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | File dengan ekstensi ODP mewakili format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | File dengan ekstensi .OTP mewakili file template presentasi yang dibuat oleh aplikasi dalam format standar OASIS OpenDocument. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | File dengan ekstensi .POT mewakili file template Microsoft PowerPoint yang dibuat oleh versi PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | File dengan ekstensi POTM adalah file template Microsoft PowerPoint dengan dukungan untuk Macro. File POTM dibuat dengan PowerPoint 2007 atau lebih tinggi dan berisi pengaturan default yang dapat digunakan untuk membuat file presentasi lebih lanjut. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | File dengan ekstensi .POTX mewakili presentasi template Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 dan yang lebih baru. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint Slide Show, file dibuat menggunakan Microsoft PowerPoint untuk keperluan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | File dengan ekstensi PPSM mewakili format file Peragaan Slide dengan Makro aktif yang dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, Peragaan Slide Power Point, file dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk tujuan Peragaan Slide. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | File dengan ekstensi PPT mewakili file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. Ini menentukan Format File Biner yang digunakan oleh Microsoft PowerPoint 97-2003. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | File dengan ekstensi PPTM adalah file Presentasi dengan Makro aktif yang dibuat dengan Microsoft PowerPoint 2007 atau versi yang lebih tinggi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | File dengan ekstensi PPTX adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Berbeda dengan versi sebelumnya dari format file presentasi PPT yang biner, format PPTX didasarkan pada format file presentasi terbuka XML Microsoft PowerPoint. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pptx) . |

### Lihat juga

* class [FileType](../filetype)
* ruang nama [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
