---
title: "VectorizationOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för vektorisering av bilder."
type: docs
weight: 2900
url: /sv/net/groupdocs.conversion.options.load/vectorizationoptions/
---
## VectorizationOptions class

Alternativ för vektorisering av bilder.

```csharp
public class VectorizationOptions : ValueObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [VectorizationOptions](vectorizationoptions)() | Standardkonstruktor för VectorizationOptions. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/vectorizationoptions/backgroundcolor) { get; set; } | Hämtar eller anger bakgrundsfärg. Standardvärdet är transparent vitt. |
| [ColorsLimit](../../groupdocs.conversion.options.load/vectorizationoptions/colorslimit) { get; set; } | Hämtar eller anger det maximala antalet färger som används för att kvantisera en bild. Standardvärdet är 25. |
| [EnableVectorization](../../groupdocs.conversion.options.load/vectorizationoptions/enablevectorization) { get; set; } | Aktivera vektorisering av bilder. Standard är false. |
| [ImageSizeLimit](../../groupdocs.conversion.options.load/vectorizationoptions/imagesizelimit) { get; set; } | Hämtar eller anger maximal dimension för bilden som bestäms av multiplikation av bildens bredd och höjd. Bildens storlek kommer att skalas baserat på denna egenskap. Standardvärdet är 1800000. |
| [LineWidth](../../groupdocs.conversion.options.load/vectorizationoptions/linewidth) { get; set; } | Hämtar eller anger linjebredden. Värdet på denna parameter påverkas av grafikskalan. Standardvärdet är 1. |
| [Severity](../../groupdocs.conversion.options.load/vectorizationoptions/severity) { get; set; } | Ställer in allvarlighetsgrad för bildspårningsutjämning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
