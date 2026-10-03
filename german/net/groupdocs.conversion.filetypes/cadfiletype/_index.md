---
title: "CadFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert CAD-Dokumente (Computer Aided Design), die für 3D-Grafikdateiformate verwendet werden und 2D- oder 3D-Designs enthalten können. Enthält die folgenden Typen Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. Erfahren Sie mehr über CAD-Formate hierhttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /de/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Definiert CAD-Dokumente (Computer Aided Design), die für 3D-Grafikdateiformate verwendet werden und 2D- oder 3D-Designs enthalten können. Enthält die folgenden Typen: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). Erfahren Sie mehr über CAD-Formate [hier](https://wiki.fileformat.com/cad).

```csharp
public sealed class CadFileType : FileType
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CadFileType](cadfiletype)() | Serialisierungskonstruktor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dateitypbeschreibung |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Die Dateierweiterung |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Die Dateifamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Das Dateiformat |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergleicht das aktuelle Objekt mit einem anderen. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementiert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als Standard-Hashfunktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String-Darstellung |

## Fields

| Name | Beschreibung |
| --- | --- |
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Gemeinsame Dateiformatdatei. CAD-Datei, die 3D-Paketdesigns oder andere Modelldaten enthält; kann von einer CAD/CAM-Maschine, wie einem Stanzgerät, verarbeitet und geschnitten werden. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN‑Dateien sind Zeichnungen, die von CAD-Anwendungen wie MicroStation und Intergraph Interactive Graphics Design System erstellt und unterstützt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) stellt 2D/3D-Zeichnungen im komprimierten Format zum Anzeigen, Überprüfen oder Drucken von Designdateien dar. Es enthält Grafiken und Text als Teil der Designdaten und reduziert die Dateigröße dank seines komprimierten Formats. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX-Datei ist eine 2D- oder 3D-Zeichnung, die mit Autodesk CAD-Software erstellt wurde. Sie wird im DWFx-Format gespeichert, das einem . DWF‑Dateiformat ähnlich ist, jedoch mit Microsofts XML Paper Specification (XPS) formatiert wird. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Dateien mit der DWG-Erweiterung stellen proprietäre Binärdateien dar, die 2D- und 3D-Designdaten enthalten. Wie DXF, das ASCII-Dateien sind, repräsentiert DWG das binäre Dateiformat für CAD‑(Computer Aided Design)‑Zeichnungen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Eine DWT-Datei ist eine AutoCAD-Zeichnungsvorlagendatei, die als Ausgangspunkt für die Erstellung von Zeichnungen verwendet wird, die als DWG-Dateien gespeichert werden können. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format oder Drawing Exchange Format, ist eine getaggte Datenrepräsentation einer AutoCAD-Zeichnungsdatei. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Dateien mit der IFC-Erweiterung beziehen sich auf das Industry Foundation Classes (IFC)-Dateiformat, das internationale Standards zum Import und Export von Bauobjekten und deren Eigenschaften festlegt. Dieses Dateiformat ermöglicht Interoperabilität zwischen verschiedenen Softwareanwendungen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs-Dokumentformat |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Das PLT-Dateiformat ist eine vektorbasiertes Plotterdatei, die von Autodesk, Inc. eingeführt wurde und Informationen für eine bestimmte CAD-Datei enthält. Plotdetails erfordern Genauigkeit und Präzision in der Produktion, und die Verwendung von PLT-Dateien garantiert dies, da alle Bilder mit Linien statt Punkten gedruckt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, Abkürzung für Stereolithografie, ist ein austauschbares Dateiformat, das die dreidimensionale Oberflächengeometrie darstellt. Das Dateiformat wird in mehreren Bereichen wie Rapid Prototyping, 3D-Druck und computergestützter Fertigung verwendet. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/cad/stl). |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
