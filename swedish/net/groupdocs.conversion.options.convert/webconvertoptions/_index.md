---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till Web-filtyp."
type: docs
weight: 2320
url: /sv/net/groupdocs.conversion.options.convert/webconvertoptions/
---
## WebConvertOptions class

Alternativ för konvertering till Web-filtyp.

```csharp
public class WebConvertOptions : CommonConvertOptions<WebFileType>, IUsePdfConvertOptions, 
    IZoomConvertOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WebConvertOptions](webconvertoptions)() | Initierar en ny instans av klassen [`WebConvertOptions`](../webconvertoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [EmbedFontResources](../../groupdocs.conversion.options.convert/webconvertoptions/embedfontresources) { get; set; } | Anger om teckensnittresurser ska bäddas in i huvud‑HTML. Standard är falskt. Obs: Om FixedLayout är satt till true kommer teckensnittresurser alltid att bäddas in. |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Om `true` används fast layout, t.ex. absolut positionerade html‑element. Standard: true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Visa sidramar vid konvertering till fast layout. Standard är True. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementerar [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementerar [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementerar [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SlideShow](../../groupdocs.conversion.options.convert/webconvertoptions/slideshow) { get; set; } | Gäller endast vid konvertering av en presentation till [`Html`](../../groupdocs.conversion.filetypes/webfiletype/html) eller [`Htm`](../../groupdocs.conversion.filetypes/webfiletype/htm), och ignoreras för alla andra konverteringar. Anger om presentationen blir ett interaktivt HTML‑bildspel med bildövergångar och formanimationer, istället för den standardmässiga statiska HTML‑sidan. Standard är false. |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Om `true` konverteras först indata till PDF och därefter till önskat format. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementerar [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Anger zoomnivån i procent. Standard är 100. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WebFileType](../../groupdocs.conversion.filetypes/webfiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
