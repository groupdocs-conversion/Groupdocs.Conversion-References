---
title: "WithOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Ange konverteringsalternativ"
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Ange konverteringsalternativ

```csharp
public IConversionByPageHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOptions | ConvertOptions | Konverteringsalternativ |

### Returvärde

Gränssnitt för att fortsätta konverteringsbyggnad

### Se även

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Ange konverteringsalternativ

```csharp
public IConversionByPageHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Konvertera alternativ Den [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Returvärde

Gränssnitt för att fortsätta konverteringsbyggnad

### Se även

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
