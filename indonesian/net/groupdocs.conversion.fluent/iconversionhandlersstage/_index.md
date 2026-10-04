---
title: "IConversionHandlersStage"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Tahap handler konversi yang diratakan. Memungkinkan mengatur OnConversionCompleted atau OnConversionFailed dalam urutan apa pun dan berulang kali sebelum melanjutkan ke Convert / Compress. Event harus didaftarkan pada tahap awal melalui WithEvents./iconversionsettings/withevents alih‑alih di tahap ini."
type: docs
weight: 1480
url: /id/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

Tahap handler konversi yang diratakan. Memungkinkan mengatur `OnConversionCompleted` atau `OnConversionFailed` dalam urutan apa pun dan berulang kali, sebelum melanjutkan ke `Convert` / `Compress`. Event harus didaftarkan pada tahap awal melalui [`WithEvents`](../iconversionsettings/withevents) alih‑alih di tahap ini.

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | Mendaftarkan callback yang akan dipanggil ketika konversi dokumen selesai dengan sukses. Memanggil kembali menggantikan handler yang sebelumnya telah diatur. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | Mendaftarkan callback yang akan dipanggil ketika konversi dokumen gagal. Memanggil kembali menggantikan handler yang sebelumnya telah diatur. |

### Lihat Juga

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
