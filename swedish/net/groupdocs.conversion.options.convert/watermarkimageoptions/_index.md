---
title: "WatermarkImageOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att ställa in vattenstämpel i det konverterade dokumentet"
type: docs
weight: 2290
url: /sv/net/groupdocs.conversion.options.convert/watermarkimageoptions/
---
## WatermarkImageOptions class

Alternativ för att ställa in vattenstämpel i det konverterade dokumentet

```csharp
public sealed class WatermarkImageOptions : WatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WatermarkImageOptions](watermarkimageoptions)(byte[]) | Skapa WatermarkOptions-klass och ange vattenmärkestext |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Skala automatiskt vattenmärket. Om värdet är sant beräknas position och storlek automatiskt för att passa sidstorleken. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Indikerar att vattenmärket är stämplat som bakgrund. Om värdet är sant placeras vattenmärket längst ner. Som standard är falskt och vattenmärket placeras överst. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Vattenmärkeshöjd |
| [Image](../../groupdocs.conversion.options.convert/watermarkimageoptions/image) { get; } | Bildvattenmärke |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Vattenmärkets vänstra position |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Vattenmärkets rotationsvinkel |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Vattenmärkets övre position |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Vattenmärkets transparens. Värde mellan 0 och 1. Värde 0 är helt synligt, värde 1 är osynligt. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Vattenmärkets bredd |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Klona aktuell instans |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [WatermarkOptions](../watermarkoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
