---
title: "IConversionSettings"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Siapkan pengaturan konversi atau peristiwa pada tahap masuk sebelum Load."
type: docs
weight: 1540
url: /id/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

Siapkan pengaturan konversi atau event pada tahap masuk (sebelum `Load`).

```csharp
public interface IConversionSettings
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | Daftarkan penangan peristiwa siklus hidup konversi pada kantong [`ConversionEvents`](../../groupdocs.conversion/conversionevents) yang hidup selama masa pakai konverter dan dipicu pada setiap proses konversi. Berada pada tahap masuk yang sama dengan [`WithSettings`](./withsettings). Beberapa pemanggilan akan terakumulasi: kantong internal yang sama diteruskan ke setiap aksi *configure*, sehingga penangan yang ditetapkan pada pemanggilan sebelumnya tetap ada kecuali ditimpa oleh yang lebih baru. |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | Atur pengaturan konverter |

### Lihat Juga

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
