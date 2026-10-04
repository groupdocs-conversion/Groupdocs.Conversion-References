---
title: "FontTransformation"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menjelaskan konfigurasi transformasi font termasuk atribut font. Transformasi font diterapkan setelah pemuatan dokumen dan substitusi font."
type: docs
weight: 260
url: /id/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

Menjelaskan konfigurasi transformasi font termasuk atribut font. Transformasi font diterapkan setelah pemuatan dokumen dan substitusi font.

```csharp
public class FontTransformation : ValueObject
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | Jika true, mencocokkan ukuran font apa pun untuk nama font asli. Jika false, mencocokkan ukuran font tepat yang ditentukan dalam OriginalFont. |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | Jika true, mencocokkan gaya font apa pun (bold, italic, underline) untuk font asli. Jika false, mencocokkan gaya font tepat yang ditentukan dalam OriginalFont. |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | Spesifikasi font asli untuk dicocokkan dan diganti. |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | Spesifikasi font pengganti. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | Membuat transformasi font dengan pencocokan font yang tepat (ukuran dan gaya harus cocok). |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | Membuat transformasi font hanya berdasarkan nama, mencocokkan ukuran dan gaya apa pun. Font pengganti akan mempertahankan ukuran dan gaya font asli. |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | Membuat transformasi font dengan opsi pencocokan yang fleksibel. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
