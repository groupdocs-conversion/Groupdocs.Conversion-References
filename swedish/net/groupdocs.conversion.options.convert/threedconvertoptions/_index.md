---
title: "ThreeDConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till 3D-typ."
type: docs
weight: 2250
url: /sv/net/groupdocs.conversion.options.convert/threedconvertoptions/
---
## ThreeDConvertOptions class

Alternativ för konvertering till 3D-typ.

```csharp
public class ThreeDConvertOptions : ConvertOptions<ThreeDFileType>, IPagedConvertOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ThreeDConvertOptions](threedconvertoptions)() | Initierar en ny instans av [`ThreeDConvertOptions`](../threedconvertoptions) klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/threedconvertoptions/pagenumber) { get; set; } | Implementerar [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [PagesCount](../../groupdocs.conversion.options.convert/threedconvertoptions/pagescount) { get; set; } | Implementerar [`PagesCount`](../ipagedconvertoptions/pagescount) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [ThreeDFileType](../../groupdocs.conversion.filetypes/threedfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
