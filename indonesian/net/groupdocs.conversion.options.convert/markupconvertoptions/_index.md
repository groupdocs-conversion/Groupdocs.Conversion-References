---
title: MarkupConvertOptions
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Opsi untuk konversi ke jenis file Markup.
type: docs
weight: 1680
url: /id/net/groupdocs.conversion.options.convert/markupconvertoptions/
---
## MarkupConvertOptions class

Opsi untuk konversi ke jenis file Markup.

```csharp
[Obsolete("This class will be removed in Conversion.NET 23.3. Please use WebConvertOptions instead.")]
public class MarkupConvertOptions : WebConvertOptions
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Jika`BENAR` tata letak tetap akan digunakan misalnya elemen html benar-benar diposisikan Default: true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Tampilkan batas halaman saat mengonversi ke tata letak tetap. Standarnya adalah Benar. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Jenis file yang diinginkan untuk konversi dokumen masukan. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Jenis file yang diinginkan untuk konversi dokumen masukan. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Nomor halaman untuk memulai konversi. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Daftar indeks halaman yang akan dikonversi. Harus ditentukan untuk mengonversi halaman tertentu. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Jumlah halaman yang akan dikonversi mulai dari`Nomor halaman` . |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Jika`BENAR` , input terlebih dahulu dikonversi ke PDF dan setelah itu ke format yang diinginkan |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opsi khusus tanda air |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Menentukan tingkat pembesaran dalam persentase. Standarnya adalah 100. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klon instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat juga

* class [WebConvertOptions](../webconvertoptions)
* ruang nama [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->