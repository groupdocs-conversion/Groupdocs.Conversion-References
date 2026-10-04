---
title: "PclLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in Pcl-dokument."
type: docs
weight: 2730
url: /sv/net/groupdocs.conversion.options.load/pclloadoptions/
---
## PclLoadOptions class

Alternativ för att läsa in Pcl-dokument.

```csharp
public sealed class PclLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PclLoadOptions](pclloadoptions)() | Initierar en ny instans av [`PclLoadOptions`](../pclloadoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/pclloadoptions/format) { get; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pclloadoptions/resetfontfolders) { get; set; } | Återställ teckensnittsmappar innan dokumentet laddas |

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
