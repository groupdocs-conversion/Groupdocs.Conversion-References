---
title: "VcfLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in Vcf-dokument."
type: docs
weight: 2890
url: /sv/net/groupdocs.conversion.options.load/vcfloadoptions/
---
## VcfLoadOptions class

Alternativ för att läsa in Vcf-dokument.

```csharp
public sealed class VcfLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [VcfLoadOptions](vcfloadoptions)() | Initierar en ny instans av [`VcfLoadOptions`](../vcfloadoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.load/vcfloadoptions/encoding) { get; set; } | Hämtar eller anger kodningen som ska användas vid inläsning av Vcf-dokument. Standard är Encoding.Default. |
| [Format](../../groupdocs.conversion.options.load/vcfloadoptions/format) { get; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
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
