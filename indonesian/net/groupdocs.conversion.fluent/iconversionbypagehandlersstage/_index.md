---
title: "IConversionByPageHandlersStage"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Tahap penangan konversi bypage yang diratakan. Cermin perpage dari IConversionHandlersStage./iconversionhandlersstage."
type: docs
weight: 1320
url: /id/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

Tahap penangan konversi by-page yang diratakan. Cermin per-page dari [`IConversionHandlersStage`](../iconversionhandlersstage).

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | Mendaftarkan callback yang akan dipanggil ketika konversi halaman selesai dengan sukses. Memanggil kembali akan menggantikan penangan yang sebelumnya telah disetel. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | Mendaftarkan callback yang akan dipanggil ketika konversi halaman gagal. Memanggil kembali akan menggantikan penangan yang sebelumnya telah disetel. |

### Lihat Juga

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
