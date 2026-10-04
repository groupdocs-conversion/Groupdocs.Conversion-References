---
title: "CadConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till Cad-typ."
type: docs
weight: 1730
url: /sv/net/groupdocs.conversion.options.convert/cadconvertoptions/
---
## CadConvertOptions class

Alternativ för konvertering till Cad-typ.

```csharp
public class CadConvertOptions : ConvertOptions<CadFileType>, IPagedConvertOptions, IPageSizeOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CadConvertOptions](cadconvertoptions)() | Initierar en ny instans av [`CadConvertOptions`](../cadconvertoptions) klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/cadconvertoptions/pagenumber) { get; set; } | Implementerar [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [PagesCount](../../groupdocs.conversion.options.convert/cadconvertoptions/pagescount) { get; set; } | Implementerar [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SizeSettings](../../groupdocs.conversion.options.convert/cadconvertoptions/sizesettings) { get; set; } | Inställningar för sidstorlek |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [CadFileType](../../groupdocs.conversion.filetypes/cadfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
