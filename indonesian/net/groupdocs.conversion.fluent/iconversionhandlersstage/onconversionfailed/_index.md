---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi dokumen gagal. Memanggil kembali akan menggantikan handler yang sebelumnya telah diatur."
type: docs
weight: 20
url: /id/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed/
---
## IConversionHandlersStage.OnConversionFailed method

Mendaftarkan callback yang akan dipanggil ketika konversi dokumen gagal. Memanggil kembali menggantikan handler yang sebelumnya telah diatur.

```csharp
public IConversionHandlersStage OnConversionFailed(Action<ConvertedContext, Exception> onFailed)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| onFailed | Action`2 | Aksi untuk menangani kegagalan, menerima konteks konversi dan pengecualian yang menyebabkan kegagalan. |

### Nilai Kembali

Tahap ini, sehingga handler tambahan atau `Convert` / `Compress` dapat dirantai.

### Lihat Juga

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
