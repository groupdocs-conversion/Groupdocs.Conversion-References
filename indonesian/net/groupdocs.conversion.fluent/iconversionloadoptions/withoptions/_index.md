---
title: "WithOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Atur opsi pemuatan"
type: docs
weight: 10
url: /id/net/groupdocs.conversion.fluent/iconversionloadoptions/withoptions/
---
## WithOptions(LoadOptions) {#withoptions}

Atur opsi pemuatan

```csharp
public IConversionSourceDocumentLoaded WithOptions(LoadOptions loadOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| loadOptions | LoadOptions | Opsi muat |

### Lihat Juga

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;LoadContext, LoadOptions&gt;) {#withoptions_1}

Sediakan opsi pemuatan untuk dokumen yang sedang dimuat

```csharp
public IConversionSourceDocumentLoaded WithOptions(
    Func<LoadContext, LoadOptions> loadOptionsProvider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| loadOptionsProvider | Func`2 | Penyedia opsi muat Konteks opsi muat |

### Lihat Juga

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadContext](../../../groupdocs.conversion/loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
