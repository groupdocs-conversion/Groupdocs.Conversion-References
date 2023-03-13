---
title: CadFileType
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Definiert CADDokumente Computer Aided Design die für 3DGrafikdateiformate verwendet werden und 2D oder 3DDesigns enthalten können. Umfasst die folgenden Typen Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . Erfahren Sie mehr über CADFormateHierhttps//wiki.fileformat.com/cad .
type: docs
weight: 860
url: /de/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Definiert CAD-Dokumente (Computer Aided Design), die für 3D-Grafikdateiformate verwendet werden und 2D- oder 3D-Designs enthalten können. Umfasst die folgenden Typen: [`Cf2`](./cf2)[`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwfx`](./dwfx)[`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . Erfahren Sie mehr über CAD-Formate[Hier](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [CadFileType](cadfiletype)() | Serialisierungskonstruktor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Beschreibung des Dateityps |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Die Dateiendung |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Die Dateifamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Das Dateiformat |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergleicht aktuelles Objekt mit anderem. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als Standard-Hash-Funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Zeichenfolgendarstellung |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Gemeinsame Dateiformatdatei. CAD-Datei, die 3D-Verpackungsentwürfe oder andere Modelldaten enthält; kann von einer CAD/CAM-Maschine verarbeitet und geschnitten werden, z. B. einem Stanzgerät. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, Dateien sind Zeichnungen, die von CAD-Anwendungen wie MicroStation und Intergraph Interactive Graphics Design System erstellt und unterstützt werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) stellt 2D/3D-Zeichnungen in komprimiertem Format zum Anzeigen, Überprüfen oder Drucken von Designdateien dar. Es enthält Grafiken und Text als Teil der Designdaten und reduziert die Dateigröße aufgrund seines komprimierten Formats. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX-Datei ist eine 2D- oder 3D-Zeichnung, die mit Autodesk CAD-Software erstellt wurde. Es wird im DWFx-Format gespeichert, das einer . DWF-Datei, ist jedoch mit der XML Paper Specification (XPS) von Microsoft formatiert. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Dateien mit der Erweiterung DWG stellen proprietäre Binärdateien dar, die zum Enthalten von 2D- und 3D-Konstruktionsdaten verwendet werden. Wie DXF, bei denen es sich um ASCII-Dateien handelt, repräsentiert DWG das binäre Dateiformat für CAD-Zeichnungen (Computer Aided Design). Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Eine DWT-Datei ist eine AutoCAD-Zeichnungsvorlagendatei, die als Starter zum Erstellen von Zeichnungen verwendet wird, die als DWG-Dateien gespeichert werden können. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format oder Drawing Exchange Format, ist eine getaggte Datendarstellung der AutoCAD-Zeichnungsdatei. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Dateien mit der Erweiterung IFC beziehen sich auf das Dateiformat Industry Foundation Classes (IFC), das internationale Standards für den Import und Export von Gebäudeobjekten und deren Eigenschaften festlegt. Dieses Dateiformat bietet Interoperabilität zwischen verschiedenen Softwareanwendungen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs-Dokumentformat |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Das PLT-Dateiformat ist eine vektorbasierte Plotterdatei, die von Autodesk, Inc. eingeführt wurde und Informationen für eine bestimmte CAD-Datei enthält. Das Plotten von Details erfordert Genauigkeit und Präzision in der Produktion, und die Verwendung von PLT-Dateien garantiert dies, da alle Bilder mit Linien anstelle von Punkten gedruckt werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, Abkürzung für Stereolithrographie, ist ein austauschbares Dateiformat, das dreidimensionale Oberflächengeometrie darstellt. Das Dateiformat findet seine Verwendung in verschiedenen Bereichen wie Rapid Prototyping, 3D-Druck und computergestützte Fertigung. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/stl) . |

### Siehe auch

* class [FileType](../filetype)
* namensraum [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
