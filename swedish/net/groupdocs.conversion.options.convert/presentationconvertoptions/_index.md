---
title: "PresentationConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Beskriver alternativ för konvertering till presentationsfiltyp."
type: docs
weight: 2170
url: /sv/net/groupdocs.conversion.options.convert/presentationconvertoptions/
---
## PresentationConvertOptions class

Beskriver alternativ för konvertering till presentationsfiltyp.

```csharp
public class PresentationConvertOptions : CommonConvertOptions<PresentationFileType>, 
    IPasswordConvertOptions, IZoomConvertOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PresentationConvertOptions](presentationconvertoptions)() | Initierar en ny instans av [`PresentationConvertOptions`](../presentationconvertoptions)-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementerar [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementerar [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementerar [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/presentationconvertoptions/password) { get; set; } | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementerar [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/presentationconvertoptions/zoom) { get; set; } | Anger zoomnivån i procent. Standard är 100. Standardzoom stöds fram till Microsoft PowerPoint 2010. Från och med Microsoft PowerPoint 2013 sätts standardzoomen inte längre till dokumentet, utan den verkar använda zoomfaktorn från det senast öppnade dokumentet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PresentationFileType](../../groupdocs.conversion.filetypes/presentationfiletype)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
