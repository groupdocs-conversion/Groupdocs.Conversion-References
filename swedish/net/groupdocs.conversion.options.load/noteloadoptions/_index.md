---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in One‑dokument"
type: docs
weight: 2680
url: /sv/net/groupdocs.conversion.options.load/noteloadoptions/
---
## NoteLoadOptions class

Alternativ för att läsa in One‑dokument

```csharp
public sealed class NoteLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [NoteLoadOptions](noteloadoptions)() | Initierar en ny instans av [`NoteLoadOptions`](../noteloadoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/noteloadoptions/defaultfont) { get; set; } | Standardteckensnitt för Note-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/noteloadoptions/fontsubstitutes) { get; set; } | Ersätt specifika teckensnitt vid konvertering av Note-dokument. |
| [Format](../../groupdocs.conversion.options.load/noteloadoptions/format) { get; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [Password](../../groupdocs.conversion.options.load/noteloadoptions/password) { get; set; } | Ange lösenord för att avskydda skyddat dokument. |

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
