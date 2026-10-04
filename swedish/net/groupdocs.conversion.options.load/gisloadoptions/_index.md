---
title: "GisLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in GIS‑dokument."
type: docs
weight: 2540
url: /sv/net/groupdocs.conversion.options.load/gisloadoptions/
---
## GisLoadOptions class

Alternativ för att läsa in GIS‑dokument.

```csharp
public class GisLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [GisLoadOptions](gisloadoptions)() | Initierar en ny instans av [`GisLoadOptions`](../gisloadoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gisloadoptions/format) { get; set; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Anger önskad sidhöjd för konvertering av GIS-dokument. Standard är 1000. |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Anger önskad sidbredd för konvertering av GIS-dokument. Standard är 1000. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
