---
title: "CadFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert CAD‑documenten Computer Aided Design die worden gebruikt voor 3D‑grafische bestandsformaten en kunnen 2D‑ of 3D‑ontwerpen bevatten. Bevat de volgende typen Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. Meer informatie over CAD-formaten hierhttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /nl/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Definieert CAD‑documenten (Computer Aided Design) die worden gebruikt voor 3D‑grafische bestandsformaten en kunnen 2D‑ of 3D‑ontwerpen bevatten. Bevat de volgende typen: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). Meer informatie over CAD-formaten [hier](https://wiki.fileformat.com/cad).

```csharp
public sealed class CadFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [CadFileType](cadfiletype)() | Serialisatie‑constructor |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Common File Format bestand. CAD‑bestand dat 3D‑pakketontwerpen of andere modelgegevens bevat; kan worden verwerkt en gesneden door een CAD/CAM‑machine, zoals een stansapparaat. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, bestanden zijn tekeningen die zijn gemaakt door en ondersteund worden door CAD‑toepassingen zoals MicroStation en Intergraph Interactive Graphics Design System. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) vertegenwoordigt 2D/3D‑tekeningen in een gecomprimeerd formaat voor het bekijken, beoordelen of afdrukken van ontwerpb bestanden. Het bevat graphics en tekst als onderdeel van ontwergegevens en verkleint de bestandsgrootte dankzij het gecomprimeerde formaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX-bestand is een 2D- of 3D-tekening gemaakt met Autodesk CAD-software. Het wordt opgeslagen in het DWFx-formaat, dat vergelijkbaar is met een . DWF-bestand, maar geformatteerd is met Microsoft's XML Paper Specification (XPS). |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Bestanden met de DWG-extensie vertegenwoordigen propriëtaire binaire bestanden die 2D- en 3D-ontwerpgegevens bevatten. Net als DXF, die ASCII-bestanden zijn, vertegenwoordigt DWG het binaire bestandsformaat voor CAD (Computer Aided Design)-tekeningen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Een DWT-bestand is een AutoCAD-tekeningssjabloon dat wordt gebruikt als startpunt voor het maken van tekeningen die als DWG-bestanden kunnen worden opgeslagen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, of Drawing Exchange Format, is een getagde gegevensrepresentatie van een AutoCAD-tekeningsbestand. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Bestanden met de IFC-extensie verwijzen naar het Industry Foundation Classes (IFC)-bestandsformaat dat internationale normen vastlegt voor het importeren en exporteren van bouwobjecten en hun eigenschappen. Dit bestandsformaat biedt interoperabiliteit tussen verschillende softwaretoepassingen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs-documentformaat |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Het PLT-bestandsformaat is een vectorgebaseerd plotterbestand geïntroduceerd door Autodesk, Inc. en bevat informatie voor een bepaald CAD-bestand. Plotdetails vereisen nauwkeurigheid en precisie in de productie, en het gebruik van PLT-bestanden garandeert dit omdat alle afbeeldingen worden afgedrukt met lijnen in plaats van punten. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, afkorting voor stereolithografie, is een uitwisselbaar bestandsformaat dat 3-dimensionale oppervlakgeometrie weergeeft. Het bestandsformaat wordt gebruikt in verschillende vakgebieden, zoals rapid prototyping, 3D-printen en computer-aided manufacturing. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/cad/stl). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
