---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendaftarkan callback yang akan dipanggil ketika konversi dokumen selesai dengan sukses. Memanggil kembali akan menggantikan handler yang sebelumnya telah diatur."
type: docs
weight: 10
url: /id/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted/
---
## IConversionHandlersStage.OnConversionCompleted method

Mendaftarkan callback yang akan dipanggil ketika konversi dokumen selesai dengan sukses. Memanggil kembali menggantikan handler yang sebelumnya telah diatur.

```csharp
public IConversionHandlersStage OnConversionCompleted(Action<ConvertedContext> onCompleted)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| onCompleted | Action`1 | Aksi untuk menangani penyelesaian, menerima konteks konversi. |

### Nilai Kembali

Tahap ini, sehingga handler tambahan atau `Convert` / `Compress` dapat dirantai.

### Lihat Juga

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
