---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi halaman gagal. Memanggil kembali menggantikan handler yang sebelumnya telah disetel."
type: docs
weight: 20
url: /id/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

Mendaftarkan callback yang akan dipanggil ketika konversi halaman gagal. Memanggil kembali akan menggantikan penangan yang sebelumnya telah disetel.

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| onFailed | Action`2 | Aksi untuk menangani kegagalan, menerima konteks halaman yang dikonversi dan pengecualian yang menyebabkan kegagalan. |

### Nilai Kembali

Tahap ini, sehingga handler tambahan atau `Convert` / `Compress` dapat dirantai.

### Lihat Juga

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
