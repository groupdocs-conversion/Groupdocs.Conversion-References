---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi halaman selesai dengan sukses. Memanggil kembali menggantikan handler yang sebelumnya telah disetel."
type: docs
weight: 10
url: /id/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted/
---
## IConversionByPageHandlersStage.OnConversionCompleted method

Mendaftarkan callback yang akan dipanggil ketika konversi halaman selesai dengan sukses. Memanggil kembali akan menggantikan penangan yang sebelumnya telah disetel.

```csharp
public IConversionByPageHandlersStage OnConversionCompleted(
    Action<ConvertedPageContext> onCompleted)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| onCompleted | Action`1 | Aksi untuk menangani penyelesaian, menerima konteks halaman yang dikonversi. |

### Nilai Kembali

Tahap ini, sehingga handler tambahan atau `Convert` / `Compress` dapat dirantai.

### Lihat Juga

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
