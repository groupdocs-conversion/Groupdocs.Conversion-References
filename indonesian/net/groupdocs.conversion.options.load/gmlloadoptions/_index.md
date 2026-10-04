---
title: "GmlLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen Gml."
type: docs
weight: 2550
url: /id/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

Opsi untuk memuat dokumen Gml.

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | Menginisialisasi instance baru dari kelas [`GmlLoadOptions`](../gmlloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | Tipe berkas dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Mengatur tinggi halaman yang diinginkan untuk mengonversi dokumen GIS. Defaultnya adalah 1000. |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Menentukan apakah Conversion diizinkan memuat skema XML dari Internet. Jika disetel ke false, skema dengan URI absolut yang tidak dimulai dengan ‘file://’ tidak akan dimuat. Nilai default adalah false. |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | Menentukan apakah Conversion diizinkan mengurai atribut dalam file Gml yang skema XML-nya hilang atau tidak dapat dimuat. Jika disetel ke true, pembaca Conversion tidak memerlukan keberadaan Skema XML. Nilai default adalah false. |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | Daftar pasangan URI yang dipisahkan spasi. URI pertama dalam setiap pasangan adalah URI dari namespace, URI kedua adalah Path ke skema XML dari namespace. Jika disetel ke null, Conversion akan mencoba membaca schemaLocation dari elemen root dokumen. Nilai default adalah null |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Mengatur lebar halaman yang diinginkan untuk mengonversi dokumen GIS. Defaultnya adalah 1000. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
