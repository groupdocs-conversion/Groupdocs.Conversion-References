---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in diagramdokument."
type: docs
weight: 2470
url: /sv/net/groupdocs.conversion.options.load/diagramloadoptions/
---
## DiagramLoadOptions class

Alternativ för att läsa in diagramdokument.

```csharp
public sealed class DiagramLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DiagramLoadOptions](diagramloadoptions)() | Initierar en ny instans av klassen [`DiagramLoadOptions`](../diagramloadoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/diagramloadoptions/defaultfont) { get; set; } | Standardteckensnitt för Diagram-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas. |
| [Format](../../groupdocs.conversion.options.load/diagramloadoptions/format) { get; set; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |

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
