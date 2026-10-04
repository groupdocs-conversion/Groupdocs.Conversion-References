---
title: "RasterImageLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen Gambar."
type: docs
weight: 2800
url: /id/net/groupdocs.conversion.options.load/rasterimageloadoptions/
---
## RasterImageLoadOptions class

Opsi untuk memuat dokumen Gambar.

```csharp
public sealed class RasterImageLoadOptions : BaseImageLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [RasterImageLoadOptions](rasterimageloadoptions)() | Menginisialisasi instance baru dari kelas [`RasterImageLoadOptions`](../rasterimageloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CropArea](../../groupdocs.conversion.options.load/rasterimageloadoptions/croparea) { get; set; } | Potong area gambar sebelum konversi |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Font default untuk tipe dokumen Psd, Emf, Wmf. Font berikut akan digunakan jika font tidak tersedia. |
| [Format](../../groupdocs.conversion.options.load/rasterimageloadoptions/format) { get; set; } | Tipe berkas dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | Atur ulang folder font sebelum memuat dokumen |
| [VectorizationOptions](../../groupdocs.conversion.options.load/rasterimageloadoptions/vectorizationoptions) { get; set; } | Mengatur opsi vektorisasi |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| [SetHeicConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setheicconnector)(IHeicConnector) | Atur konektor gambar Heic |
| [SetOcrConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setocrconnector)(IOcrConnector) | Atur konektor OCR gambar |

### Lihat Juga

* class [BaseImageLoadOptions](../baseimageloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
