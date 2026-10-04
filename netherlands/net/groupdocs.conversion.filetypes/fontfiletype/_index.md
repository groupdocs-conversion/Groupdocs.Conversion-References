---
title: "Lettertypebestandstype"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert lettertype-documenten Bevat de volgende typen Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Meer informatie over lettertype-indelingen hierhttps//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /nl/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Definieert lettertype-documenten Bevat de volgende typen: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Meer informatie over lettertype-indelingen [hier](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [FontFileType](fontfiletype)() | Serialisatie‑constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstypebeschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt het huidige object met een ander. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementeert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Stringrepresentatie |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Een bestand met de extensie .cff is een Compact Font Format en staat ook bekend als een PostScript Type 1, of CIDFont. CFF fungeert als een container om meerdere lettertypen samen op te slaan in één eenheid die een FontSet wordt genoemd. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Een bestand met de extensie .eot is een OpenType-lettertype dat in een document is ingebed. Deze worden meestal gebruikt in webbestanden zoals een webpagina. Het werd gemaakt door Microsoft en wordt ondersteund door Microsoft-producten, inclusief PowerPoint-presentatie .pps-bestanden. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Een bestand met de extensie .otf verwijst naar het OpenType-lettertypeformaat. Het OTF-lettertypeformaat is schaalbaarder en breidt de bestaande functies van TTF-formaten uit voor digitale typografie. Ontwikkeld door Microsoft en Adobe, combineert OTF de kenmerken van PostScript- en TrueType-lettertypeformaten. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Een bestand met de extensie .ttf vertegenwoordigt lettertypebestanden gebaseerd op de TrueType-specificaties. Het werd oorspronkelijk ontworpen en gelanceerd door Apple Computer, Inc voor Mac OS en later overgenomen door Microsoft voor Windows OS. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Type 1-lettertypen zijn een verouderde Adobe-technologie die veel werd gebruikt in desktop publishing-software en printers die PostScript konden gebruiken. Hoewel Type 1-lettertypen niet worden ondersteund op veel moderne platforms, webbrowsers en mobiele besturingssystemen, worden ze nog steeds ondersteund in sommige besturingssystemen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Een bestand met de extensie .woff is een weblettertypebestand gebaseerd op het Web Open Font Format (WOFF). Het heeft een formaat-specifieke gecomprimeerde container gebaseerd op ofwel TrueType (.TTF) of OpenType (.OTT) lettertype‑typen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Een bestand met de extensie .woff is een weblettertypebestand gebaseerd op het Web Open Font Format (WOFF). Het heeft een formaat-specifieke gecomprimeerde container gebaseerd op ofwel TrueType (.TTF) of OpenType (.OTT) lettertype‑typen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/font/woff/). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
