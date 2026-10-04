---
title: "WithOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mengatur opsi konversi untuk proses konversi."
type: docs
weight: 10
url: /id/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Mengatur opsi konversi untuk proses konversi.

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOptions | ConvertOptions | Opsi konversi. |

### Nilai Kembali

Tahap handler untuk melanjutkan pembangunan konversi.

### Lihat Juga

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Mengatur opsi konversi menggunakan fungsi penyedia.

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| optionsProvider | Func`2 | Fungsi yang menyediakan opsi konversi berdasarkan konteks konversi. |

### Nilai Kembali

Tahap handler untuk melanjutkan pembangunan konversi.

### Lihat Juga

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
