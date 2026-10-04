---
title: "EBookConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till EBook-filtyp."
type: docs
weight: 1790
url: /sv/net/groupdocs.conversion.options.convert/ebookconvertoptions/
---
## EBookConvertOptions class

Alternativ för konvertering till EBook-filtyp.

```csharp
public class EBookConvertOptions : CommonConvertOptions<EBookFileType>, IPageOrientationOptions, 
    IPageSizeOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EBookConvertOptions](ebookconvertoptions)() | Initierar en ny instans av [`EBookConvertOptions`](../ebookconvertoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/ebookconvertoptions/fallbackpagesize) { get; set; } | Reservsidstorlek |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/orientationsettings) { get; set; } | Inställningar för sidorientering |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementerar [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementerar [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementerar [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SizeSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/sizesettings) { get; set; } | Inställningar för sidstorlek |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementerar [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [EBookFileType](../../groupdocs.conversion.filetypes/ebookfiletype)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
