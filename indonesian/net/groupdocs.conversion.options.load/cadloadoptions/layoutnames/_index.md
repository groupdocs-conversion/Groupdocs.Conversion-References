---
title: "LayoutNames"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menentukan layout CAD mana yang akan dikonversi"
type: docs
weight: 70
url: /id/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

Menentukan layout CAD mana yang akan dikonversi

```csharp
public string[] LayoutNames { get; set; }
```

### Catatan

Tidak dihormati saat mengonversi ke PDF/UA-1. Target tersebut menampilkan gambar sebagai satu halaman berlabel, yang tidak dapat memuat satu lembar per tata letak yang dipilih, sehingga seluruh gambar dikonversi dan tidak ada yang berlaku di sini. Semua target lain, termasuk PDF, menghormati pemilihan tersebut. Pada target tersebut, nama dicocokkan secara tepat dengan tata letak yang dimiliki gambar, sehingga nama yang hanya berbeda huruf besar/kecil dianggap berbeda. Nama yang tidak cocok apa pun akan diabaikan dan hanya membebani pemanggil satu lembar; daftar yang tidak ada yang cocok menyebabkan konversi gagal dengan [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) yang menyebutkan nama-nama yang tidak ditemukan dan tata letak yang dimiliki gambar, alih-alih menampilkan lembar yang tidak diminta pemanggil. Gambar yang tidak memiliki tata letak sama sekali dikecualikan: tidak ada yang dapat dicocokkan, sehingga tidak ada yang ditolak.

### Lihat Juga

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
