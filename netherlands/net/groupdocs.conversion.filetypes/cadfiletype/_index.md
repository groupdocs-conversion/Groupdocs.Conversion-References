---
title: CadFileType
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert CADdocumenten Computer Aided Design die worden gebruikt voor 3D grafische bestandsindelingen en die 2D of 3Dontwerpen kunnen bevatten. Bevat de volgende typen Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . Meer informatie over CADindelingenhierhttps//wiki.fileformat.com/cad .
type: docs
weight: 860
url: /nl/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Definieert CAD-documenten (Computer Aided Design) die worden gebruikt voor 3D grafische bestandsindelingen en die 2D- of 3D-ontwerpen kunnen bevatten. Bevat de volgende typen: [`Cf2`](./cf2)[`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwfx`](./dwfx)[`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . Meer informatie over CAD-indelingen[hier](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [CadFileType](cadfiletype)() | Serialisatie-constructor |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Algemeen bestandsformaat Bestand. CAD-bestand dat 3D-pakketontwerpen of andere modelgegevens bevat; kan worden verwerkt en gesneden door een CAD/CAM-machine, zoals een stansapparaat. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, bestanden zijn tekeningen gemaakt door en ondersteund door CAD-applicaties zoals MicroStation en Intergraph Interactive Graphics Design System. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) vertegenwoordigt 2D/3D-tekeningen in gecomprimeerd formaat voor het bekijken, beoordelen of afdrukken van ontwerpbestanden. Het bevat afbeeldingen en tekst als onderdeel van ontwerpgegevens en verkleint het bestand vanwege het gecomprimeerde formaat. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX-bestand is een 2D- of 3D-tekening gemaakt met Autodesk CAD-software. Het wordt opgeslagen in het DWFx-formaat, dat vergelijkbaar is met een . DWF-bestand, maar is geformatteerd met Microsoft's XML Paper Specification (XPS). |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Bestanden met de extensie DWG vertegenwoordigen bedrijfseigen binaire bestanden die worden gebruikt voor het bevatten van 2D- en 3D-ontwerpgegevens. Net als DXF, wat ASCII-bestanden zijn, vertegenwoordigt DWG het binaire bestandsformaat voor CAD-tekeningen (Computer Aided Design). Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Een DWT-bestand is een AutoCAD-tekeningsjabloonbestand dat wordt gebruikt als starter voor het maken van tekeningen die kunnen worden opgeslagen als DWG-bestanden. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format of Drawing Exchange Format, is een gelabelde gegevensrepresentatie van een AutoCAD-tekenbestand. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Bestanden met de extensie IFC verwijzen naar het Industry Foundation Classes (IFC)-bestandsformaat dat internationale normen vaststelt voor het importeren en exporteren van bouwobjecten en hun eigenschappen. Dit bestandsformaat biedt interoperabiliteit tussen verschillende softwaretoepassingen. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs-documentformaat |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Het PLT-bestandsformaat is een op vectoren gebaseerd plotterbestand geïntroduceerd door Autodesk, Inc. en bevat informatie voor een bepaald CAD-bestand. Plotdetails vereisen nauwkeurigheid en precisie bij de productie, en het gebruik van PLT-bestanden garandeert dit, aangezien alle afbeeldingen worden afgedrukt met lijnen in plaats van punten. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, afkorting voor stereolithrografie, is een uitwisselbaar bestandsformaat dat driedimensionale oppervlaktegeometrie vertegenwoordigt. Het bestandsformaat wordt op verschillende gebieden gebruikt, zoals rapid prototyping, 3D-printen en computerondersteunde productie. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/cad/stl) . |

### Zie ook

* class [FileType](../filetype)
* naamruimte [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
