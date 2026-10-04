---
title: "WithEvents"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Daftarkan penangan peristiwa siklus hidup konversi pada sebuah ConversionEventsgroupdocs.conversion/conversionevents bag yang hidup selama masa pakai konverter dan dipicu pada setiap proses konversi. Dapat dipanggil sebelum atau sesudah WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Beberapa pemanggilan mengakumulasi; kantong internal yang sama diteruskan ke setiap aksi configure sehingga penangan yang ditetapkan pada pemanggilan sebelumnya tetap ada kecuali ditimpa oleh pemanggilan yang lebih baru."
type: docs
weight: 20
url: /id/net/groupdocs.conversion.fluent/iconversionfrom/withevents/
---
## IConversionFrom.WithEvents method

Daftarkan penangan peristiwa siklus hidup konversi pada sebuah [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) bag yang hidup selama masa pakai konverter dan dipicu pada setiap proses konversi. Dapat dipanggil sebelum atau sesudah [`WithSettings`](../../iconversionsettings/withsettings). Beberapa pemanggilan mengakumulasi: kantong internal yang sama diteruskan ke setiap aksi *configure*, sehingga penangan yang ditetapkan pada pemanggilan sebelumnya tetap ada kecuali ditimpa oleh pemanggilan yang lebih baru.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konfigurasi | Action`1 | Aksi yang mengubah kantong peristiwa. |

### Nilai Kembali

Tahap ini sehingga pemanggilan tahap masuk selanjutnya atau `Load` dapat dirantai.

### Lihat Juga

* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
