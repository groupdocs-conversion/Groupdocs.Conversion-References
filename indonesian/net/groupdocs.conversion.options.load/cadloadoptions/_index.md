---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen CAD."
type: docs
weight: 2430
url: /id/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

Opsi untuk memuat dokumen CAD.

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | Menginisialisasi instance baru dari kelas [`CadLoadOptions`](../cadloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | Mendapatkan atau mengatur warna latar belakang. |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | Mendapatkan atau mengatur sumber CTB. |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | Mendapatkan atau mengatur warna latar depan. |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | Mendapatkan atau mengatur tipe gambar. |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | Menentukan layout CAD mana yang akan dikonversi |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | Mendapatkan atau mengatur ruang gambar mana yang dikonversi. Nilai default adalah [`Both`](../cadlayoutscope/both), yang tidak membatasi konversi. Nilai ini diabaikan ketika [`LayoutNames`](./layoutnames) disediakan, karena nama layout eksplisit selalu diutamakan. Nilai `null` diperlakukan sebagai [`Both`](../cadlayoutscope/both). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
