---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Terima aliran dokumen yang dikonversi. Akan dipicu hanya jika ConvertTostring fileName atau ConvertToconvertedStreamProvider diatur."
type: docs
weight: 10
url: /id/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

Menerima aliran dokumen yang dikonversi. Akan dipicu hanya jika "ConvertTo(string fileName)" atau ConvertTo(convertedStreamProvider)" diatur.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertedFileStream | Action`1 | Penyedia aliran dokumen yang dikonversi yang [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### Nilai Kembali

Antarmuka untuk melanjutkan pembangunan konversi

### Lihat Juga

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
