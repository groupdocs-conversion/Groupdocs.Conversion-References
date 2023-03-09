---
title: DiagramFileType
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert diagramdocumenten. Bevat de volgende typen Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx .
type: docs
weight: 900
url: /nl/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Definieert diagramdocumenten. Bevat de volgende typen: [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx) .

```csharp
public sealed class DiagramFileType : FileType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Serialisatie-constructor |

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
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW is de Visio Graphics Service-bestandsindeling die de streams en opslagruimte specificeert die nodig zijn voor het renderen van een webtekening. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Elke tekening of grafiek die is gemaakt in Microsoft Visio, maar is opgeslagen in XML-indeling, heeft de extensie .VDX. Een Visio-tekening XML-bestand wordt gemaakt in Visio-software, die is ontwikkeld door Microsoft. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD-bestanden zijn tekeningen die zijn gemaakt met de Microsoft Visio-toepassing om verschillende grafische objecten en de onderlinge samenhang daartussen weer te geven. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Bestanden met de extensie VSDM zijn tekenbestanden die zijn gemaakt met de Microsoft Visio-toepassing die macro's ondersteunt. VSDM-bestanden zijn OPC/XML-tekeningen die vergelijkbaar zijn met VSDX, maar die ook de mogelijkheid bieden om macro's uit te voeren wanneer het bestand wordt geopend. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Bestanden met de extensie .VSDX vertegenwoordigen het Microsoft Visio-bestandsformaat dat vanaf Microsoft Office 2013 is geïntroduceerd. Het is ontwikkeld ter vervanging van de binaire bestandsindeling .VSD, die wordt ondersteund door eerdere versies van Microsoft Visio. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS zijn stencilbestanden die zijn gemaakt met Microsoft Visio 2007 en eerder. Stencilbestanden bieden tekenobjecten die kunnen worden opgenomen in een .VSD Visio-tekening. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vss) . |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Bestanden met de extensie .VSSM zijn Microsoft Visio Stencil-bestanden die ondersteuning bieden voor macro's. Wanneer een VSSM-bestand wordt geopend, kunnen de macro's worden uitgevoerd om de gewenste opmaak en plaatsing van vormen in een diagram te bereiken. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vssm) . |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Bestanden met de extensie .VSSX zijn tekensjablonen die zijn gemaakt met Microsoft Visio 2013 en hoger. Het VSSX-bestandsformaat kan worden geopend met Visio 2013 en hoger. Visio-bestanden staan bekend om de weergave van verschillende tekenelementen, zoals verzameling vormen, connectoren, stroomschema's, netwerklay-out, UML-diagrammen, Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vssx) . |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Bestanden met de extensie VST zijn vectorafbeeldingsbestanden die zijn gemaakt met Microsoft Visio en fungeren als sjabloon voor het maken van andere bestanden. Deze sjabloonbestanden hebben een binaire bestandsindeling en bevatten de standaardlay-out en instellingen die worden gebruikt voor het maken van nieuwe Visio-tekeningen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vst) . |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Bestanden met de extensie VSTM zijn sjabloonbestanden die zijn gemaakt met Microsoft Visio en die macro's ondersteunen. In tegenstelling tot VSDX-bestanden kunnen bestanden die zijn gemaakt op basis van VSTM-sjablonen macro's uitvoeren die zijn ontwikkeld in Visual Basic for Applications (VBA)-code. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/vstm) . |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Bestanden met VSTX-extensies zijn tekensjabloonbestanden die zijn gemaakt met Microsoft Visio 2013 en hoger. Deze VSTX-bestanden bieden een startpunt voor het maken van Visio-tekeningen, opgeslagen als .VSDX-bestanden, met standaardlay-out en instellingen. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/vstx) . |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Bestanden met de extensie .VSX verwijzen naar stencils die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. VSX-bestanden worden opgeslagen in XML-bestandsindeling en werden ondersteund tot Visio 2013. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vsx) . |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Een bestand met de VTX-extensie is een Microsoft Visio-tekeningsjabloon dat in XML-bestandsindeling op schijf wordt opgeslagen. De sjabloon is bedoeld om een bestand met basisinstellingen te bieden dat kan worden gebruikt om meerdere Visio-bestanden met dezelfde instellingen te maken. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vtx) . |

### Zie ook

* class [FileType](../filetype)
* naamruimte [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
