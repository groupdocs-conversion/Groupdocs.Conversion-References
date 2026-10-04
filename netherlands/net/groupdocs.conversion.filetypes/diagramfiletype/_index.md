---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert Diagram‑documenten. Bevat de volgende typen Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /nl/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Definieert Diagram‑documenten. Bevat de volgende typen: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Serialisatie‑constructor |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | Een bestand met de extensie DRAWIO is een diagram gemaakt met diagrams.net (voorheen draw.io). Het wordt opgeslagen in XML‑bestandsformaat met het mxfile‑hoofdelement en bevat de inhoud en opmaak van de diagram‑elementen zoals tekst, afbeeldingen, lay‑out, vormen en positionering. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | Een bestand met de extensie MMD is een diagram geschreven in de Mermaid‑opmaakt taal. Het wordt opgeslagen als een platte‑tekstdocument dat begint met de diagramdeclaratie, zoals flowchart of sequenceDiagram, gevolgd door de definitie van de knooppunten en de verbindingen daartussen. Leer meer over dit bestandsformaat [hier](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW is het Visio Graphics Service‑bestandsformaat dat de streams en opslaglocaties specificeert die nodig zijn voor het renderen van een webtekening. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Elke tekening of grafiek die in Microsoft Visio is gemaakt, maar in XML‑formaat is opgeslagen, heeft de extensie .VDX. Een Visio‑XML‑tekening wordt gemaakt in Visio‑software, die door Microsoft is ontwikkeld. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD‑bestanden zijn tekeningen gemaakt met de Microsoft Visio‑applicatie om een verscheidenheid aan grafische objecten en de onderlinge verbindingen weer te geven. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Bestanden met de VSDM-extensie zijn tekenbestanden die zijn gemaakt met de Microsoft Visio-toepassing die macro's ondersteunt. VSDM-bestanden zijn OPC/XML-tekeningen die vergelijkbaar zijn met VSDX, maar bieden ook de mogelijkheid om macro's uit te voeren wanneer het bestand wordt geopend. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Bestanden met de .VSDX-extensie vertegenwoordigen het Microsoft Visio-bestandsformaat dat is geïntroduceerd vanaf Microsoft Office 2013. Het is ontwikkeld om het binaire bestandsformaat .VSD te vervangen, dat wordt ondersteund door eerdere versies van Microsoft Visio. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS zijn sjabloonbestanden die zijn gemaakt met Microsoft Visio 2007 en eerder. Sjabloonbestanden bieden tekenobjecten die kunnen worden opgenomen in een .VSD Visio-tekening. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Bestanden met de .VSSM-extensie zijn Microsoft Visio-sjabloonbestanden die ondersteuning voor macro's bieden. Een VSSM-bestand maakt bij openen het uitvoeren van macro's mogelijk om de gewenste opmaak en plaatsing van vormen in een diagram te bereiken. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Bestanden met de .VSSX-extensie zijn tekensjablonen die zijn gemaakt met Microsoft Visio 2013 en hoger. Het VSSX-bestandsformaat kan worden geopend met Visio 2013 en hoger. Visio-bestanden staan bekend om de weergave van diverse tekenelementen, zoals een verzameling vormen, connectoren, stroomdiagrammen, netwerkindelingen, UML-diagrammen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Bestanden met de VST-extensie zijn vectorafbeeldingsbestanden die zijn gemaakt met Microsoft Visio en fungeren als sjabloon voor het maken van verdere bestanden. Deze sjabloonbestanden zijn in een binair bestandsformaat en bevatten de standaardlay-out en instellingen die worden gebruikt voor het creëren van nieuwe Visio-tekeningen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Bestanden met de VSTM-extensie zijn sjabloonbestanden die zijn gemaakt met Microsoft Visio en macro's ondersteunen. In tegenstelling tot VSDX-bestanden kunnen bestanden die zijn gemaakt vanuit VSTM-sjablonen macro's uitvoeren die zijn ontwikkeld in Visual Basic for Applications (VBA)-code. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Bestanden met de VSTX-extensie zijn tekensjabloonbestanden die zijn gemaakt met Microsoft Visio 2013 en hoger. Deze VSTX-bestanden bieden een startpunt voor het maken van Visio-tekeningen, opgeslagen als .VSDX-bestanden, met een standaardlay-out en instellingen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Bestanden met de .VSX-extensie verwijzen naar sjablonen die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. VSX-bestanden worden opgeslagen in XML-bestandsformaat en werden ondersteund tot Visio 2013. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Een bestand met de VTX-extensie is een Microsoft Visio-teken-sjabloon dat op schijf wordt opgeslagen in XML-bestandsformaat. Het sjabloon is bedoeld om een bestand met basisinstellingen te bieden dat kan worden gebruikt om meerdere Visio-bestanden met dezelfde instellingen te maken. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vtx). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
