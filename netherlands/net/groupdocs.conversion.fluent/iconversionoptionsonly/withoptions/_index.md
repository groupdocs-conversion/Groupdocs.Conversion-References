---
title: "WithOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Stelt conversieopties in voor het conversieproces."
type: docs
weight: 10
url: /nl/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Stelt conversieopties in voor het conversieproces.

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertOptions | ConvertOptions | Conversie‑opties. |

### Retourwaarde

Handlers‑fase om de conversieopbouw voort te zetten.

### Zie ook

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Stelt conversieopties in met behulp van een provider‑functie.

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| optionsProvider | Func`2 | Een functie die conversie‑opties levert op basis van de conversie‑context. |

### Retourwaarde

Handlers‑fase om de conversieopbouw voort te zetten.

### Zie ook

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
