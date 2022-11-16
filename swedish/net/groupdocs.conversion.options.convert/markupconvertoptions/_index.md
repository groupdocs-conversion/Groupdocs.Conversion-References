---
title: MarkupConvertOptions
second_title: GroupDocs.Conversion for .NET API Referens
description: Alternativ för konvertering till Markup filtyp.
type: docs
weight: 1520
url: /sv/net/groupdocs.conversion.options.convert/markupconvertoptions/
---
## MarkupConvertOptions class

Alternativ för konvertering till Markup filtyp.

```csharp
public class MarkupConvertOptions : CommonConvertOptions<MarkupFileType>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MarkupConvertOptions](markupconvertoptions)() | Initierar ny instans av[`MarkupConvertOptions`](../markupconvertoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [FixedLayout](../../groupdocs.conversion.options.convert/markupconvertoptions/fixedlayout) { get; set; } | Om`Sann` fast layout kommer att användas t.ex. absolut positionerade html elements Standard: true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/markupconvertoptions/fixedlayoutshowborders) { get; set; } | Visa sidkanter vid konvertering till fast layout. Standard är True. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Sidnumret att börja konverteringen från. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Listan över sidindex som ska konverteras. Bör specificeras för att konvertera specifika sidor. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Antal sidor att konvertera från`Sidonummer` . |
| [UsePdf](../../groupdocs.conversion.options.convert/markupconvertoptions/usepdf) { get; set; } | Om`Sann` , indata konverteras först till PDF och därefter till önskat format |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Vattenstämpelspecifika alternativ |
| [Zoom](../../groupdocs.conversion.options.convert/markupconvertoptions/zoom) { get; set; } | Anger zoomnivån i procent. Standard är 100. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar nuvarande alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standard hash-funktion. |

### Se även

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [MarkupFileType](../../groupdocs.conversion.filetypes/markupfiletype)
* namnutrymme [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->