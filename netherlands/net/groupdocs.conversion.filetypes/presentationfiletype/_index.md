---
title: "PresentatieBestandstype"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert presentatiedocumentformaten die een verzameling records opslaan om presentatiedata zoals dia's, vormen, tekst, animaties, video, audio en ingesloten objecten te huisvesten. Bevat de volgende bestandstypen Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. Meer informatie over presentatieformaten hierhttps//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /nl/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Definieert presentatiedocumentformaten die een verzameling records opslaan om presentatiedata zoals dia's, vormen, tekst, animaties, video, audio en ingesloten objecten te huisvesten. Bevat de volgende bestandstypen: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). Meer informatie over presentatieformaten [hier](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Serialisatie‑constructor |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Bestanden met de extensie FODP vertegenwoordigen OpenDocument Flat XML Presentation. Presentatiedocument opgeslagen in het OpenDocument‑formaat, maar opgeslagen met een plat XML‑formaat in plaats van de .ZIP‑container die wordt gebruikt door standaard .ODP‑bestanden. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Bestanden met de extensie ODP vertegenwoordigen het presentatiedocumentformaat dat wordt gebruikt door OpenOffice.org in de OASISOpen‑standaard. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Bestanden met de extensie .OTP vertegenwoordigen presentatiesjabloonbestanden die zijn gemaakt door applicaties in het OASIS OpenDocument‑standaardformaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Bestanden met de extensie .POT vertegenwoordigen Microsoft PowerPoint‑sjabloonbestanden die zijn gemaakt door PowerPoint‑versies 97‑2003. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Bestanden met de extensie POTM zijn Microsoft PowerPoint‑sjabloonbestanden met ondersteuning voor macro's. POTM‑bestanden worden gemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om verdere presentatiedocumenten te maken. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Bestanden met de extensie .POTX vertegenwoordigen Microsoft PowerPoint‑sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint Slide Show, bestanden worden gemaakt met Microsoft PowerPoint voor presentatiedoeleinden. Het lezen en maken van PPS‑bestanden wordt ondersteund door Microsoft PowerPoint 97‑2003. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Bestanden met de extensie PPSM vertegenwoordigen een macro‑ingeschakelde Slide Show‑bestandsindeling die is gemaakt met Microsoft PowerPoint 2007 of hoger. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, Power Point Slide Show, bestanden worden gemaakt met Microsoft PowerPoint 2007 en hoger voor presentatiedoeleinden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Een bestand met de extensie PPT vertegenwoordigt een PowerPoint‑bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. Het specificeert het binaire bestandsformaat dat wordt gebruikt door Microsoft PowerPoint 97‑2003. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Bestanden met de extensie PPTM zijn macro‑ingeschakelde presentatiedocumenten die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Bestanden met de PPTX-extensie zijn presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint-toepassing. In tegenstelling tot de vorige versie van het presentatiebestandformaat PPT, dat binair was, is het PPTX-formaat gebaseerd op het open XML-presentatiebestandformaat van Microsoft PowerPoint. Meer informatie over dit bestandformaat [hier](https://wiki.fileformat.com/presentation/pptx). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
