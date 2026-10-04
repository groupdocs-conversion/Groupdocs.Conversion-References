---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in Txt-dokument."
type: docs
weight: 2870
url: /sv/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Alternativ för att läsa in Txt-dokument.

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | Initierar en ny instans av [`TxtLoadOptions`](../txtloadoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | Typsnitt att använda vid rendering av vanlig textinnehåll under konvertering. Eftersom TXT-filer inte innehåller typsnittsinformation specificerar denna egenskap visningstypsnittet för textinnehållet. Standard: Arial 10pt. |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | Tillåter att ange hur numrerade listobjekt identifieras när ett vanligt textdokument konverteras. Standardvärdet är true. |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Hämtar eller anger kodningen som ska användas vid inläsning av Txt-dokument. Kan vara null. Standard är null. |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | Hämtar eller anger föredragen inställning för hantering av inledande mellanslag. Standardvärdet är [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent). |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | Inställningar för sidmarginaler |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | Inställningar för sidstorlek |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | Hämtar eller anger föredragen inställning för hantering av avslutande mellanslag. Standardvärdet är [`Trim`](../txttrailingspacesoptions/trim). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Anmärkningar

**Font Configuration for Plain Text:**

Eftersom TXT-filer inte innehåller typsnittsinformation, använd DefaultTextFont för att ange

typsnittet för rendering av det vanliga textinnehållet under konvertering.

### Se även

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
