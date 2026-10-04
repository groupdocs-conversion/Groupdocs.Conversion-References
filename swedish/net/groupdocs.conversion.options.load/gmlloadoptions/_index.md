---
title: "GmlLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in Gml‑dokument."
type: docs
weight: 2550
url: /sv/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

Alternativ för att läsa in Gml‑dokument.

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | Initierar en ny instans av klassen [`GmlLoadOptions`](../gmlloadoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Anger önskad sidhöjd för konvertering av GIS-dokument. Standard är 1000. |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Avgör om konvertering får ladda XML‑schema från internet. Om den är falsk kommer scheman med absoluta URI:er som inte börjar med ‘file://’ inte att laddas. Standard är falskt. |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | Bestämmer om Conversion får tolka attribut i en Gml‑fil där ett XML‑schema saknas eller inte kan läsas in. Om den är satt till true kräver inte Conversion‑läsaren närvaron av ett XML‑schema. Standardvärdet är false. |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | Mellanslagsseparerad lista med URI‑par. Den första URI:n i varje par är en URI för namnrymden, den andra URI:n är en sökväg till XML‑schemat för namnrymden. Om den är satt till null försöker Conversion läsa schemaLocation från dokumentets rottag. Standardvärdet är null |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Anger önskad sidbredd för konvertering av GIS-dokument. Standard är 1000. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
