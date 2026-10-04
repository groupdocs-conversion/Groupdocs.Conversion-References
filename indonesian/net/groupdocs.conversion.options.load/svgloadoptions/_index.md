---
title: "SvgLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen Svg."
type: docs
weight: 2830
url: /id/net/groupdocs.conversion.options.load/svgloadoptions/
---
## SvgLoadOptions class

Opsi untuk memuat dokumen Svg.

```csharp
public class SvgLoadOptions : LoadOptions, IResourceLoadingOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | Menginisialisasi instance baru dari kelas [`SvgLoadOptions`](../svgloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CropToContentBounds](../../groupdocs.conversion.options.load/svgloadoptions/croptocontentbounds) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan memotong kotak pembatas SVG ke batas konten sebelum konversi. Nilai default adalah false. |
| [Format](../../groupdocs.conversion.options.load/svgloadoptions/format) { get; set; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [MinimumHeight](../../groupdocs.conversion.options.load/svgloadoptions/minimumheight) { get; set; } | Atur tinggi minimum untuk mengonversi dokumen SVG. Ini digunakan saat mengonversi ke format raster. Nilai default adalah 600. |
| [MinimumWidth](../../groupdocs.conversion.options.load/svgloadoptions/minimumwidth) { get; set; } | Atur lebar minimum untuk mengonversi dokumen SVG. Ini digunakan saat mengonversi ke format raster. Nilai default adalah 800. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/svgloadoptions/skipexternalresources) { get; set; } | Menerapkan [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/svgloadoptions/whitelistedresources) { get; set; } | Sumber daya eksternal yang akan selalu dimuat. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [LoadOptions](../loadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
