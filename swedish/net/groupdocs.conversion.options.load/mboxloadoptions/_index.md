---
title: "MboxLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in Mbox‑dokument."
type: docs
weight: 2670
url: /sv/net/groupdocs.conversion.options.load/mboxloadoptions/
---
## MboxLoadOptions class

Alternativ för att läsa in Mbox‑dokument.

```csharp
public sealed class MboxLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MboxLoadOptions](mboxloadoptions)() | Initierar en ny instans av klassen [`MboxLoadOptions`](../mboxloadoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/mboxloadoptions/convertowned) { get; } | Implementerar [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) skrivskyddad. Sätt till true. De ägda dokumenten kommer att konverteras. |
| [ConvertOwner](../../groupdocs.conversion.options.load/mboxloadoptions/convertowner) { get; } | Implementerar [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) skrivskyddad. Sätt till false. Ägaren kommer inte att konverteras. |
| [Depth](../../groupdocs.conversion.options.load/mboxloadoptions/depth) { get; set; } | Implementerar [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Standard: 3 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/mboxloadoptions/clone)() | Klonar aktuell instans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
