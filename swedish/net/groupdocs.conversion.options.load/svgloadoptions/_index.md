---
title: "SvgLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in Svg-dokument."
type: docs
weight: 2830
url: /sv/net/groupdocs.conversion.options.load/svgloadoptions/
---
## SvgLoadOptions class

Alternativ för att läsa in Svg-dokument.

```csharp
public class SvgLoadOptions : LoadOptions, IResourceLoadingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | Initierar en ny instans av klassen [`SvgLoadOptions`](../svgloadoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CropToContentBounds](../../groupdocs.conversion.options.load/svgloadoptions/croptocontentbounds) { get; set; } | Hämtar eller anger ett värde som indikerar om SVG‑begränsningsrutan ska beskäras till innehållsgränserna före konvertering. Standardvärdet är falskt. |
| [Format](../../groupdocs.conversion.options.load/svgloadoptions/format) { get; set; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [MinimumHeight](../../groupdocs.conversion.options.load/svgloadoptions/minimumheight) { get; set; } | Ställ in minsta höjd för konvertering av SVG-dokument. Den används vid konvertering till rasterformat. Standard är 600. |
| [MinimumWidth](../../groupdocs.conversion.options.load/svgloadoptions/minimumwidth) { get; set; } | Ställ in minsta bredd för konvertering av SVG-dokument. Den används vid konvertering till rasterformat. Standard är 800. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/svgloadoptions/skipexternalresources) { get; set; } | Implementerar [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/svgloadoptions/whitelistedresources) { get; set; } | Externa resurser som alltid kommer att laddas. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [LoadOptions](../loadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
