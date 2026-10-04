---
title: "ConversionEvents"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menggabungkan penangan peristiwa siklus hidup konversi. Berikan sebuah instance ke parameter events konstruktor Converter./converter atau ke metode fluent WithEvents. Lebih disarankan menggunakan ini daripada properti penangan individual ConverterSettings./convertersettings yang sudah usang."
type: docs
weight: 850
url: /id/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

Menggabungkan penangan peristiwa siklus hidup konversi. Berikan sebuah instance ke parameter `events` konstruktor [`Converter`](../converter) atau ke metode fluent `WithEvents`. Lebih disarankan menggunakan ini daripada properti penangan individual [`ConverterSettings`](../convertersettings), yang sudah usang.

```csharp
public sealed class ConversionEvents
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ConversionEvents](conversionevents)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | Dipicu ketika kompresi output konversi selesai. Hanya dipanggil pada build yang menyertakan pipeline kompresi (LIB_ZIP). |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | Dipicu sekali ketika proses konversi selesai, terlepas dari keberhasilan atau kegagalan. |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | Dipicu secara berkala dengan kemajuan konversi dalam persentase (0–100). |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | Dipicu sekali pada awal proses konversi, sebelum dokumen apa pun diproses. |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | Dipicu sekali per konversi seluruh dokumen yang selesai dengan sukses. |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | Dipicu sekali per konversi seluruh dokumen yang gagal. |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | Dipicu ketika font yang dirujuk oleh dokumen sumber tidak tersedia dan digantikan (baik oleh aturan [`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute) yang disediakan pelanggan, oleh font default yang dikonfigurasi, atau oleh fallback internal pipeline konversi). |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | Dipicu sekali per halaman ketika konversi per halaman selesai dengan sukses. |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | Dipicu sekali per halaman ketika konversi per halaman gagal. |

### Lihat Juga

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
