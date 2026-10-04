---
title: "WithEvents"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Daftarkan penangan peristiwa siklus hidup konversi pada sebuah tas ConversionEventsgroupdocs.conversion/conversionevents yang hidup selama masa pakai konverter dan dipicu pada setiap proses konversi. Terletak pada tahap masuk yang sama seperti WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Beberapa panggilan mengakumulasi, tas internal yang sama diteruskan ke setiap aksi configure sehingga penangan yang ditetapkan pada panggilan sebelumnya tetap ada kecuali ditimpa oleh panggilan selanjutnya."
type: docs
weight: 10
url: /id/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

Daftarkan penangan peristiwa siklus hidup konversi pada sebuah tas [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) yang hidup selama masa pakai konverter dan dipicu pada setiap proses konversi. Terletak pada tahap masuk yang sama seperti [`WithSettings`](../withsettings). Beberapa panggilan mengakumulasi: tas internal yang sama diteruskan ke setiap aksi *configure*, sehingga penangan yang ditetapkan pada panggilan sebelumnya tetap ada kecuali ditimpa oleh panggilan berikutnya.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konfigurasi | Action`1 | Aksi yang mengubah kantong peristiwa. |

### Nilai Kembali

Tahap pemilihan sumber sehingga `Load` dapat dirantai.

### Lihat Juga

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
