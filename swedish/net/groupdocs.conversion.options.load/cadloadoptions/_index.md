---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in CAD‑dokument."
type: docs
weight: 2430
url: /sv/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

Alternativ för att läsa in CAD‑dokument.

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | Initierar en ny instans av klassen [`CadLoadOptions`](../cadloadoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | Hämtar eller anger en bakgrundsfärg. |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | Hämtar eller anger CTB-källorna. |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | Hämtar eller anger förgrundsfärg. |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | Hämtar eller anger typ av ritning. |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | Anger vilka CAD‑layouter som ska konverteras |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | Hämtar eller anger vilka ritningsutrymmen som konverteras. Standardvärdet är [`Both`](../cadlayoutscope/both), vilket inte begränsar konverteringen. Det ignoreras när [`LayoutNames`](./layoutnames) anges, eftersom explicita layoutnamn alltid har företräde. Ett `null`‑värde behandlas som [`Both`](../cadlayoutscope/both). |

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
