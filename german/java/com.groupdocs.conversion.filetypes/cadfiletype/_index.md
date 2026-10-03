---
title: "CadFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert CAD‑Dokumente (Computer Aided Design), die für 3D‑Grafikdateiformate verwendet werden und 2D‑ oder 3D‑Entwürfe enthalten können."
type: docs
weight: 11
url: /de/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

Definiert CAD-Dokumente (Computer Aided Design), die für 3D‑Grafikdateiformate verwendet werden und 2D‑ oder 3D‑Designs enthalten können.
Enthält die folgenden Typen:
[Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype#Dgn),
[Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwf),
[Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwg),
[Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwt),
[Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dxf),
[Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype#Ifc),
[Igs](../../com.groupdocs.conversion.filetypes/cadfiletype#Igs),
[Plt](../../com.groupdocs.conversion.filetypes/cadfiletype#Plt),
[Stl](../../com.groupdocs.conversion.filetypes/cadfiletype#Stl).
[Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype#Cf2).
[Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwfx).
Erfahren Sie mehr über CAD‑Formate [hier](../https://wiki.fileformat.com/cad).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Dxf](#Dxf) | DXF, Drawing Interchange Format oder Drawing Exchange Format, ist eine getaggte Datenrepräsentation einer AutoCAD‑Zeichnungsdatei. |
|
|  | [Dwg](#Dwg) | Dateien mit der Erweiterung DWG stellen proprietäre Binärdateien dar, die 2D‑ und 3D‑Designdaten enthalten. |
|
|  | [Dgn](#Dgn) | DGN‑Dateien (Design) sind Zeichnungen, die von CAD‑Anwendungen wie MicroStation und Intergraph Interactive Graphics Design System erstellt und unterstützt werden. |
|
|  | [Dwf](#Dwf) | Design Web Format (DWF) stellt 2D/3D‑Zeichnungen in komprimiertem Format zum Anzeigen, Überprüfen oder Drucken von Design‑Dateien dar. |
|
|  | [Stl](#Stl) | STL, die Abkürzung für Stereolithografie, ist ein austauschbares Dateiformat, das dreidimensionale Oberflächengeometrie darstellt. |
|
|  | [Ifc](#Ifc) | Dateien mit der Erweiterung IFC beziehen sich auf das Industry Foundation Classes (IFC)‑Dateiformat, das internationale Standards zum Import und Export von Bauobjekten und deren Eigenschaften festlegt. |
|
|  | [Plt](#Plt) | Das PLT‑Dateiformat ist eine vektorbasierte Plotterdatei, die von Autodesk, Inc. eingeführt wurde. |
|
|  | [Igs](#Igs) | Igs‑Dokumentenformat |
|
|  | [Dwt](#Dwt) | Eine DWT‑Datei ist eine AutoCAD‑Zeichnungsvorlagendatei, die als Ausgangspunkt für das Erstellen von Zeichnungen dient, die als DWG‑Dateien gespeichert werden können. |
|
|  | [Dwfx](#Dwfx) | DWFX‑Datei ist eine 2D‑ oder 3D‑Zeichnung, die mit Autodesk‑CAD‑Software erstellt wurde. |
|
|  | [Cf2](#Cf2) | Common File Format Datei. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Serialisierungskonstruktor


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF, Drawing Interchange Format oder Drawing Exchange Format, ist eine getaggte Datenrepräsentation einer AutoCAD‑Zeichnungsdatei.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


DFiles mit DWG-Erweiterung stellen proprietäre Binärdateien dar, die 2D- und 3D-Design-Daten enthalten. Wie DXF, das ASCII-Dateien sind, repräsentiert DWG das binäre Dateiformat für CAD (Computer Aided Design)-Zeichnungen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN‑Dateien (Design) sind Zeichnungen, die von CAD‑Anwendungen wie MicroStation und Intergraph Interactive Graphics Design System erstellt und unterstützt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) stellt 2D/3D-Zeichnungen im komprimierten Format zum Anzeigen, Überprüfen oder Drucken von Design-Dateien dar. Es enthält Grafiken und Text als Teil der Design-Daten und reduziert die Dateigröße dank seines komprimierten Formats.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, Abkürzung für Stereolithografie, ist ein austauschbares Dateiformat, das die dreidimensionale Oberflächengeometrie darstellt. Das Dateiformat wird in mehreren Bereichen wie Rapid Prototyping, 3D-Druck und computergestützter Fertigung verwendet.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


Dateien mit IFC-Erweiterung beziehen sich auf das Industry Foundation Classes (IFC)-Dateiformat, das internationale Standards zum Import und Export von Bauobjekten und deren Eigenschaften festlegt. Dieses Dateiformat bietet Interoperabilität zwischen verschiedenen Softwareanwendungen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


Das PLT-Dateiformat ist eine vektorbasierte Plotterdatei, die von Autodesk, Inc. eingeführt wurde und Informationen für eine bestimmte CAD-Datei enthält. Plotdetails erfordern Genauigkeit und Präzision in der Produktion, und die Verwendung der PLT-Datei garantiert dies, da alle Bilder mit Linien statt Punkten gedruckt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Igs‑Dokumentenformat


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


Eine DWT‑Datei ist eine AutoCAD‑Zeichnungsvorlagendatei, die als Ausgangspunkt für das Erstellen von Zeichnungen dient, die als DWG‑Dateien gespeichert werden können.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


DWFX-Datei ist eine 2D- oder 3D-Zeichnung, die mit Autodesk CAD-Software erstellt wurde. Sie wird im DWFx-Format gespeichert, das einem .DWF-File ähnelt, jedoch mit Microsofts XML Paper Specification (XPS) formatiert ist.


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Common File Format File. CAD-Datei, die 3D-Paketdesigns oder andere Modelldaten enthält; kann von einer CAD/CAM-Maschine, wie einem Stanzgerät, verarbeitet und geschnitten werden.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Standard‑Ladeoptionen für den Quelldateityp vorbereitet


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Standard‑Konvertierungsoptionen für den Dateityp vorbereitet


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
