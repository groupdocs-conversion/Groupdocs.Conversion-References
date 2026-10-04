---
title: "WithOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Anger konverteringsalternativ för konverteringsprocessen."
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Anger konverteringsalternativ för konverteringsprocessen.

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOptions | ConvertOptions | Konverteringsalternativ. |

### Returvärde

Hanterarsteg för att fortsätta konverteringsbyggnad.

### Se även

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Anger konverteringsalternativ med en leverantörsfunktion.

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| optionsProvider | Func`2 | En funktion som tillhandahåller konverteringsalternativ baserat på konverteringskontexten. |

### Returvärde

Hanterarsteg för att fortsätta konverteringsbyggnad.

### Se även

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
