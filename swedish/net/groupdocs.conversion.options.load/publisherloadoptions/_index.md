---
title: "PublisherLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in Publisher-dokument."
type: docs
weight: 2790
url: /sv/net/groupdocs.conversion.options.load/publisherloadoptions/
---
## PublisherLoadOptions class

Alternativ för att läsa in Publisher-dokument.

```csharp
public class PublisherLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PublisherLoadOptions](publisherloadoptions)() | Initierar en ny instans av klassen [`PublisherLoadOptions`](../publisherloadoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/publisherloadoptions/defaultfont) { get; set; } | Standardteckensnitt för Publisher-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/publisherloadoptions/fontsubstitutes) { get; set; } | Ersätt specifika teckensnitt vid konvertering av Publisher-dokument. |
| [Format](../../groupdocs.conversion.options.load/publisherloadoptions/format) { get; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
