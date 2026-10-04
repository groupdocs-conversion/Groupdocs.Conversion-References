---
title: "CompressionLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in komprimeringsdokument."
type: docs
weight: 2440
url: /sv/net/groupdocs.conversion.options.load/compressionloadoptions/
---
## CompressionLoadOptions class

Alternativ för att läsa in komprimeringsdokument.

```csharp
public sealed class CompressionLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CompressionLoadOptions](compressionloadoptions)() | Initierar en ny instans av [`CompressionLoadOptions`](../compressionloadoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/compressionloadoptions/convertowned) { get; } | Implementerar [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) skrivskyddad. Sätt till true. De ägda dokumenten kommer att konverteras. |
| [ConvertOwner](../../groupdocs.conversion.options.load/compressionloadoptions/convertowner) { get; } | Implementerar [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) skrivskyddad. Sätt till false. Ägaren kommer inte att konverteras. |
| [Depth](../../groupdocs.conversion.options.load/compressionloadoptions/depth) { get; set; } | Implementerar [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Standard: 3 |
| [Format](../../groupdocs.conversion.options.load/compressionloadoptions/format) { get; set; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [Password](../../groupdocs.conversion.options.load/compressionloadoptions/password) { get; set; } | Ange lösenord för att läsa in skyddat dokument. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
