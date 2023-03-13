---
title: PresentationFileType
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert presentatiebestandsindelingen waarin een verzameling records wordt opgeslagen voor presentatiegegevens zoals dias vormen tekst animaties video audio en ingesloten objecten. Bevat de volgende bestandstypen Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . Meer informatie over presentatieindelingenhierhttps//wiki.fileformat.com/presentation .
type: docs
weight: 1020
url: /nl/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Definieert presentatiebestandsindelingen waarin een verzameling records wordt opgeslagen voor presentatiegegevens zoals dia's, vormen, tekst, animaties, video, audio en ingesloten objecten. Bevat de volgende bestandstypen: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . Meer informatie over presentatie-indelingen[hier](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Serialisatie-constructor |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Bestanden met de FODP-extensie vertegenwoordigen OpenDocument Flat XML-presentatie. Presentatiebestand opgeslagen in de OpenDocument-indeling, maar opgeslagen met een platte XML-indeling in plaats van de .ZIP-container die wordt gebruikt door standaard .ODP files |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Bestanden met de ODP-extensie vertegenwoordigen het presentatiebestandsformaat dat wordt gebruikt door OpenOffice.org in de OASISOpen-standaard. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Bestanden met de extensie .OTP vertegenwoordigen presentatiesjabloonbestanden gemaakt door toepassingen in de OASIS OpenDocument-standaardindeling. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Bestanden met de extensie .POT vertegenwoordigen Microsoft PowerPoint-sjabloonbestanden gemaakt door PowerPoint 97-2003-versies. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Bestanden met de POTM-extensie zijn Microsoft PowerPoint-sjabloonbestanden met ondersteuning voor macro's. POTM-bestanden worden gemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om meer presentatiebestanden te maken. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Bestanden met de extensie .POTX vertegenwoordigen Microsoft PowerPoint-sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint-diavoorstelling, bestanden worden gemaakt met behulp van Microsoft PowerPoint voor diavoorstellingen. Het lezen en maken van PPS-bestanden wordt ondersteund door Microsoft PowerPoint 97-2003. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Bestanden met de PPSM-extensie vertegenwoordigen de bestandsindeling Diavoorstelling met macro's die is gemaakt met Microsoft PowerPoint 2007 of hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, PowerPoint-diavoorstelling, bestanden worden gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Een bestand met PPT-extensie vertegenwoordigt een PowerPoint-bestand dat bestaat uit een verzameling dia's voor weergave als SlideShow. Het specificeert de binaire bestandsindeling die wordt gebruikt door Microsoft PowerPoint 97-2003. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Bestanden met de PPTM-extensie zijn presentatiebestanden met macro's die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Bestanden met de extensie PPTX zijn presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint-toepassing. In tegenstelling tot de vorige versie van het presentatiebestandsformaat PPT, dat binair was, is het PPTX-formaat gebaseerd op het Microsoft PowerPoint open XML-presentatiebestandsformaat. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/presentation/pptx) . |

### Zie ook

* class [FileType](../filetype)
* naamruimte [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
