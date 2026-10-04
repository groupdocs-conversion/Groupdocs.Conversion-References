---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Terima aliran halaman yang dikonversi. Akan dipicu hanya jika ConvertToconvertedStreamProvider diatur."
type: docs
weight: 10
url: /id/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Terima aliran halaman yang dikonversi. Akan dipicu hanya jika "ConvertTo(convertedStreamProvider)" diatur.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertedPageStream | Action`1 | Penyedia aliran halaman yang dikonversi [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### Nilai Kembali

Antarmuka untuk melanjutkan pembangunan konversi

### Lihat Juga

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
