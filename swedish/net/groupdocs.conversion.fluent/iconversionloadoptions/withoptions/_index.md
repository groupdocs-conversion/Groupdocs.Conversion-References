---
title: "WithOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Ange laddningsalternativ"
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversionloadoptions/withoptions/
---
## WithOptions(LoadOptions) {#withoptions}

Ange laddningsalternativ

```csharp
public IConversionSourceDocumentLoaded WithOptions(LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loadOptions | LoadOptions | Laddningsalternativ |

### Se även

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;LoadContext, LoadOptions&gt;) {#withoptions_1}

Tillhandahåll laddningsalternativ för dokumentet som för närvarande laddas

```csharp
public IConversionSourceDocumentLoaded WithOptions(
    Func<LoadContext, LoadOptions> loadOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loadOptionsProvider | Func`2 | Laddningsalternativleverantör Kontext för laddningsalternativ |

### Se även

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadContext](../../../groupdocs.conversion/loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
