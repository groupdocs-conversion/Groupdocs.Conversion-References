---
title: "WithOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Atur opsi konversi"
type: docs
weight: 10
url: /id/net/groupdocs.conversion.fluent/iconversionconvertoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Atur opsi konversi

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOptions | ConvertOptions | Opsi konversi |

### Nilai Kembali

Antarmuka untuk melanjutkan pembangunan konversi

### Lihat Juga

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Atur opsi konversi

```csharp
public IConversionHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Parameter | Deskripsi |
| --- | --- |
| convertOptionsProvider | Penyedia opsi konversi |
| convertOptionsProvider arg1arg1 | Yang [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Nilai Kembali

Antarmuka untuk melanjutkan pembangunan konversi

### Lihat Juga

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
