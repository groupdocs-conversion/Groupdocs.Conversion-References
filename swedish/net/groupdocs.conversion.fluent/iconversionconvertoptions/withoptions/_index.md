---
title: "WithOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Ange konverteringsalternativ"
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversionconvertoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Ange konverteringsalternativ

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOptions | ConvertOptions | Konverteringsalternativ |

### Returvärde

Gränssnitt för att fortsätta konverteringsbyggnad

### Se även

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Ange konverteringsalternativ

```csharp
public IConversionHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Parameter | Beskrivning |
| --- | --- |
| convertOptionsProvider | Leverantör av konverteringsalternativ |
| convertOptionsProvider arg1arg1 | Den [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Returvärde

Gränssnitt för att fortsätta konverteringsbyggnad

### Se även

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
