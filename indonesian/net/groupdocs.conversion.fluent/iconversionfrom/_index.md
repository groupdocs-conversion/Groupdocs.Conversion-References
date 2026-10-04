---
title: "IConversionFrom"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Siapkan sumber untuk konversi"
type: docs
weight: 1440
url: /id/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

Siapkan sumber untuk konversi

```csharp
public interface IConversionFrom
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | Atur aliran dokumen sumber |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | Atur array aliran dokumen sumber |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | Atur nama file dokumen sumber |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | Atur array dokumen sumber |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | Daftarkan penangan peristiwa siklus hidup konversi pada kantong [`ConversionEvents`](../../groupdocs.conversion/conversionevents) yang hidup selama masa pakai konverter dan dipicu pada setiap proses konversi. Dapat dipanggil sebelum atau setelah [`WithSettings`](../iconversionsettings/withsettings). Pemanggilan berulang akan terakumulasi: kantong internal yang sama diteruskan ke setiap aksi *configure*, sehingga penangan yang diatur pada pemanggilan sebelumnya tetap ada kecuali ditimpa oleh pemanggilan berikutnya. |

### Lihat Juga

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
