---
title: FontFileType
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert lettertypedocumenten Bevat de volgende typen Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Meer informatie over lettertypeindelingenhierhttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /nl/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Definieert lettertypedocumenten Bevat de volgende typen: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Meer informatie over lettertype-indelingen[hier](https://docs.fileformat.com/font/) .

```csharp
public sealed class FontFileType : FileType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [FontFileType](fontfiletype)() | Serialisatie-constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstype omschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt huidige object met andere. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Tekenreeksweergave |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Een bestand met de extensie .cff is een Compact Font Format en wordt ook wel PostScript Type 1 of CIDFont genoemd. CFF fungeert als een container om meerdere lettertypen samen op te slaan in een enkele eenheid die bekend staat als een FontSet. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Een bestand met de extensie .eot is een OpenType-lettertype dat is ingesloten in een document. Deze worden meestal gebruikt in webbestanden zoals een webpagina. Het is gemaakt door Microsoft en wordt ondersteund door Microsoft-producten, waaronder PowerPoint-presentatie .pps-bestand. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Een bestand met de extensie .otf verwijst naar het OpenType-lettertypeformaat. Het OTF-lettertypeformaat is beter schaalbaar en breidt de bestaande functies van TTF-indelingen voor digitale typografie uit. OTF is ontwikkeld door Microsoft en Adobe en combineert de kenmerken van PostScript- en TrueType-lettertypeformaten. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Een bestand met de extensie .ttf vertegenwoordigt lettertypebestanden op basis van de lettertypetechnologie van TrueType-specificaties. Het is oorspronkelijk ontworpen en gelanceerd door Apple Computer, Inc voor Mac OS en werd later overgenomen door Microsoft voor Windows OS. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Type 1-lettertypen is een verouderde Adobe-technologie die veel werd gebruikt in de desktop-based publishing-software en printers die PostScript konden gebruiken. Hoewel Type 1-lettertypen niet worden ondersteund in veel moderne platforms, webbrowsers en mobiele besturingssystemen, worden deze nog steeds ondersteund in sommige besturingssystemen. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Een bestand met de extensie .woff is een weblettertypebestand dat is gebaseerd op het Web Open Font Format (WOFF). Het heeft een indelingsspecifieke gecomprimeerde container op basis van TrueType (.TTF) of OpenType (.OTT) lettertypen. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Een bestand met de extensie .woff is een weblettertypebestand dat is gebaseerd op het Web Open Font Format (WOFF). Het heeft een indelingsspecifieke gecomprimeerde container op basis van TrueType (.TTF) of OpenType (.OTT) lettertypen. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/font/woff/) . |

### Zie ook

* class [FileType](../filetype)
* naamruimte [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
