---
title: "WithEvents"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Varian tahap masuk dari rantai fluent yang dimulai dengan penangan peristiwa siklus hidup konversi. Terletak pada tahap masuk yang sama dengan WithSettingsgroupdocs.conversion/fluentconverter/withsettings dan kantong ConversionEventsgroupdocs.conversion/conversionevents yang dihasilkan dipicu pada setiap proses konversi oleh konverter."
type: docs
weight: 20
url: /id/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

Varian tahap masuk dari rantai fluent yang dimulai dengan penangan peristiwa siklus hidup konversi. Terletak pada tahap masuk yang sama dengan [`WithSettings`](../withsettings), dan kantong [`ConversionEvents`](../../conversionevents) yang dihasilkan dipicu pada setiap proses konversi oleh konverter.

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konfigurasi | Action`1 | Aksi yang mengubah kantong peristiwa. |

### Nilai Kembali

Tahap pemilihan sumber sehingga `Load` dapat dirantai.

### Lihat Juga

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
