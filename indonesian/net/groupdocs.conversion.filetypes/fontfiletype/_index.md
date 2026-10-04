---
title: "FontFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan dokumen Font Menyertakan tipe berikut Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Pelajari lebih lanjut tentang format Font di sinihttps//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /id/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Mendefinisikan dokumen Font Menyertakan tipe berikut: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Pelajari lebih lanjut tentang format Font [di sini](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FontFileType](fontfiletype)() | Konstruktor Serialisasi |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | File dengan ekstensi .cff adalah Compact Font Format dan juga dikenal sebagai PostScript Type 1, atau CIDFont. CFF berfungsi sebagai wadah untuk menyimpan beberapa font bersama dalam satu unit yang disebut FontSet. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | File dengan ekstensi .eot adalah font OpenType yang disematkan dalam sebuah dokumen. Ini biasanya digunakan dalam file web seperti halaman Web. Font ini dibuat oleh Microsoft dan didukung oleh Produk Microsoft termasuk presentasi PowerPoint .pps. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | File dengan ekstensi .otf mengacu pada format font OpenType. Format font OTF lebih skalabel dan memperluas fitur yang ada pada format TTF untuk tipografi digital. Dikembangkan oleh Microsoft dan Adobe, OTF menggabungkan fitur format font PostScript dan TrueType. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | File dengan ekstensi .ttf mewakili file font yang berbasis pada teknologi font spesifikasi TrueType. Awalnya dirancang dan diluncurkan oleh Apple Computer, Inc untuk Mac OS dan kemudian diadopsi oleh Microsoft untuk Windows OS. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Font Type 1 adalah teknologi Adobe yang sudah usang dan sebelumnya banyak digunakan dalam perangkat lunak penerbitan berbasis desktop serta printer yang dapat menggunakan PostScript. Meskipun font Type 1 tidak didukung di banyak platform modern, peramban web, dan sistem operasi seluler, namun masih didukung di beberapa sistem operasi. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | File dengan ekstensi .woff adalah file font web yang berbasis pada Web Open Font Format (WOFF). Ia memiliki wadah terkompresi khusus format yang berbasis pada jenis font TrueType (.TTF) atau OpenType (.OTT). Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | File dengan ekstensi .woff adalah file font web yang berbasis pada Web Open Font Format (WOFF). Ia memiliki wadah terkompresi khusus format yang berbasis pada jenis font TrueType (.TTF) atau OpenType (.OTT). Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/font/woff/). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
