---
title: "ConvertTo"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Sla geconverteerd document op als bestand"
type: docs
weight: 20
url: /nl/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

Sla geconverteerd document op als bestand

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Geconverteerd document |

### Retourwaarde

Opties of handler‑instellingsinterface om de conversieopbouw voort te zetten

### Zie ook

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

Sla geconverteerd document op als stream

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Provider voor documentstream van geconverteerd document De opslagcontext |

### Retourwaarde

Opties of handler‑instellingsinterface om de conversieopbouw voort te zetten

### Zie ook

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
