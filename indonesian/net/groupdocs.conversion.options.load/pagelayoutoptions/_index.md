---
title: "PageLayoutOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menjelaskan mode tata letak halaman saat memuat dokumen web."
type: docs
weight: 2720
url: /id/net/groupdocs.conversion.options.load/pagelayoutoptions/
---
## PageLayoutOptions class

Menjelaskan mode tata letak halaman saat memuat dokumen web.

```csharp
public class PageLayoutOptions : FlagsEnumeration
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan objek lain. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Menentukan apakah dua instance objek sama. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | Memeriksa apakah flag saat ini memiliki flag yang ditentukan. |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | Memeriksa apakah flag saat ini memiliki nilai yang ditentukan. |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | Mengonversi objek saat ini menjadi string. |
| [operator &#x7C;](../../groupdocs.conversion.options.load/pagelayoutoptions/op_bitwiseor) | Menggabungkan dua flag [`PageLayoutOptions`](../pagelayoutoptions) menggunakan OR bitwise. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [None](../../groupdocs.conversion.options.load/pagelayoutoptions/none) | Nilai default |
| static readonly [ScaleToPageHeight](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopageheight) | Flag ini menunjukkan bahwa konten dokumen akan diskalakan agar sesuai dengan tinggi halaman pertama. Semua konten dokumen akan ditempatkan hanya pada satu halaman. |
| static readonly [ScaleToPageWidth](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopagewidth) | Menunjukkan bahwa konten dokumen akan diskalakan agar sesuai dengan halaman di mana selisih antara lebar halaman yang tersedia dan konten yang tumpang tindih paling besar. |

### Lihat Juga

* class [FlagsEnumeration](../../groupdocs.conversion.contracts/flagsenumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
