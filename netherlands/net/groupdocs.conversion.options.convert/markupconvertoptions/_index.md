---
title: MarkupConvertOptions
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Opties voor conversie naar Markupbestandstype.
type: docs
weight: 1680
url: /nl/net/groupdocs.conversion.options.convert/markupconvertoptions/
---
## MarkupConvertOptions class

Opties voor conversie naar Markup-bestandstype.

```csharp
[Obsolete("This class will be removed in Conversion.NET 23.3. Please use WebConvertOptions instead.")]
public class MarkupConvertOptions : WebConvertOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Als`WAAR` vaste lay-out wordt gebruikt, bijv. absoluut gepositioneerd html elementen Standaard: true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Toon paginaranden bij conversie naar vaste lay-out. Standaard is True. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Het paginanummer vanaf waar de conversie moet worden gestart. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | De lijst met pagina-indexen die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Aantal pagina's om vanaf te converteren`Paginanummer` . |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Als`WAAR` , wordt de invoer eerst geconverteerd naar PDF en daarna naar gewenst formaat |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Watermerkspecifieke opties |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Specificeert het zoomniveau in procenten. Standaard is 100. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Kloont de huidige optie-instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [WebConvertOptions](../webconvertoptions)
* naamruimte [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->