---
title: "MarkdownOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till markdown-filtyp."
type: docs
weight: 2010
url: /sv/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

Alternativ för konvertering till markdown-filtyp.

```csharp
public sealed class MarkdownOptions : ValueObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | Initierar en ny instans av klassen [`MarkdownOptions`](../markdownoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | Exportera bilder som base64. Standard är true. Ignoreras när [`ImageSavingCallback`](./imagesavingcallback) är satt. |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | Återanrop som anropas en gång per bild vid sparande av Markdown. Låter anroparen lagra bilder externt och ersätta URI:n som är inbäddad i dokumentet. Har företräde framför [`ExportImagesAsBase64`](./exportimagesasbase64) när den inte är null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
