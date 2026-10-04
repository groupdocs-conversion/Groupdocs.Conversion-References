---
title: "WithOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Stel conversieopties in"
type: docs
weight: 10
url: /nl/net/groupdocs.conversion.fluent/iconversionconvertoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Stel conversieopties in

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertOptions | ConvertOptions | Conversieopties |

### Retourwaarde

Interface om de conversieopbouw voort te zetten

### Zie ook

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Stel conversieopties in

```csharp
public IConversionHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Parameter | Beschrijving |
| --- | --- |
| convertOptionsProvider | Provider van conversieopties |
| convertOptionsProvider arg1arg1 | De [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Retourwaarde

Interface om de conversieopbouw voort te zetten

### Zie ook

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
