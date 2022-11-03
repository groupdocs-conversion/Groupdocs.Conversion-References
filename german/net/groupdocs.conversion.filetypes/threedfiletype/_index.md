---
title: ThreeDFileType
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Definiert 3DDokumente Enthält die folgenden Typen Fbx./threedfiletype/fbx Erfahren Sie mehr über 3DFormatehierhttps//wiki.fileformat.com/3d .
type: docs
weight: 940
url: /de/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Definiert 3D-Dokumente Enthält die folgenden Typen: [`Fbx`](./fbx) Erfahren Sie mehr über 3D-Formate[hier](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serialisierungskonstruktor |

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
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als Standard-Hash-Funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Zeichenfolgendarstellung |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Eine AMF-Datei besteht aus Richtlinien für die Beschreibung von Objekten, die von Additive Manufacturing-Prozessen verwendet werden sollen. Es enthält ein öffnendes XML-Tag und endet mit einem Element. Davor steht eine XML-Deklarationszeile, die die XML-Version und die Kodierung der Datei angibt. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Eine Datei mit der Erweiterung .ase ist ein Autodesk-ASCII-Szenenexport-Dateiformat, das eine ASCII-Darstellung einer Szene ist und 2D- oder 3D-Informationen enthält, während Szenendaten mit Autodesk exportiert werden. Weitere Informationen zu diesem Dateiformat[hier](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Eine DAE-Datei ist ein Digital Asset Exchange-Dateiformat, das für den Datenaustausch zwischen interaktiven 3D-Anwendungen verwendet wird. Dieses Dateiformat basiert auf dem XML-Schema COLLADA (COLLAborative Design Activity), einem offenen Standard-XML-Schema für den Austausch digitaler Assets zwischen Grafiksoftwareanwendungen. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Eine Datei mit der Erweiterung .drc ist ein komprimiertes 3D-Dateiformat, das mit der Google Draco-Bibliothek erstellt wurde. Google bietet Draco als Open-Source-Bibliothek zum Komprimieren und Dekomprimieren von geometrischen 3D-Netzen und Punktwolken an und verbessert die Speicherung und Übertragung von 3D-Grafiken. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, ist ein beliebtes 3D-Dateiformat, das ursprünglich von Kaydara für MotionBuilder entwickelt wurde. Es wurde 2006 von Autodesk Inc übernommen und ist heute eines der wichtigsten 3D-Austauschformate, das von vielen 3D-Tools verwendet wird. FBX ist sowohl im Binär- als auch im ASCII-Dateiformat verfügbar. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) ist ein 3D-Dateiformat, das 3D-Modellinformationen im JSON-Format speichert. Die Verwendung von JSON minimiert sowohl die Größe von 3D-Assets als auch die Laufzeitverarbeitung, die zum Entpacken und Verwenden dieser Assets erforderlich ist. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) ist ein effizientes, branchenorientiertes und flexibles ISO-standardisiertes 3D-Datenformat, das von Siemens PLM Software entwickelt wurde. Mechanische CAD-Domänen der Luft- und Raumfahrt, Automobilindustrie und Schwermaschinen verwenden JT als ihr führendes 3D-Visualisierungsformat. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ-Dateien werden von der Advanced Visualizer-Anwendung von Wavefront verwendet, um die geometrischen Objekte zu definieren und zu speichern. Die Rückwärts- und Vorwärtsübertragung von geometrischen Daten wird durch OBJ-Dateien ermöglicht. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, stellt ein 3D-Dateiformat dar, das grafische Objekte speichert, die als eine Sammlung von Polygonen beschrieben werden. Der Zweck dieses Dateiformats bestand darin, einen einfachen und einfachen Dateityp zu etablieren, der allgemein genug ist, um für eine Vielzahl von Modellen nützlich zu sein. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM-Datendateien beziehen sich auf AVEVA PDMS. Die RVM-Datei ist eine AVEVA Plant Design Management System Model-Projektdatei. Das Plant Design Management System (PDMS) von AVEVA ist das beliebteste 3D-Designsystem mit datenzentrierter Technologie zur Verwaltung von Projekten. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Eine Datei mit der Erweiterung .3ds stellt das von Autodesk 3D Studio verwendete 3D Studio (DOS) Mesh-Dateiformat dar. Autodesk 3D Studio ist seit den 1990er Jahren auf dem Markt für 3D-Dateiformate und hat sich nun zu 3D Studio MAX für die Arbeit mit 3D-Modellierung, -Animation und -Rendering entwickelt. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, wird von Anwendungen verwendet, um 3D-Objektmodelle für eine Vielzahl anderer Anwendungen, Plattformen, Dienste und Drucker zu rendern. Es wurde entwickelt, um die Einschränkungen und Probleme anderer 3D-Dateiformate wie STL beim Arbeiten mit den neuesten Versionen von 3D-Druckern zu vermeiden. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) ist ein komprimiertes Dateiformat und eine Datenstruktur für 3D-Computergrafik. Es enthält 3D-Modellinformationen wie Dreiecksnetze, Beleuchtung, Schattierung, Bewegungsdaten, Linien und Punkte mit Farbe und Struktur. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Eine Datei mit der Erweiterung .usd ist ein Universal Scene Description-Dateiformat, das Daten zum Zwecke des Datenaustauschs und der Erweiterung zwischen Anwendungen zur Erstellung digitaler Inhalte codiert. USD wurde von Pixar entwickelt und bietet die Möglichkeit, elementare Assets (z. B. Modelle) oder Animationen auszutauschen. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Eine Datei mit .usdz ist ein unkomprimiertes und unverschlüsseltes ZIP-Archiv für das Dateiformat USD (Universal Scene Description), das Dateien anderer Formate (z USD-Laufzeit ohne Entpacken. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Die Virtual Reality Modeling Language (VRML) ist ein Dateiformat zur Darstellung von interaktiven 3D-Weltobjekten über das World Wide Web (www). Es findet seine Verwendung bei der Erstellung dreidimensionaler Darstellungen komplexer Szenen wie Illustrationen, Definitionen und Virtual-Reality-Präsentationen. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Eine Datei mit der Erweiterung .x bezieht sich auf das ältere Dateiformat DirectX 3D Graphics, das mit Microsoft DirectX 2.0 eingeführt wurde. Es wurde zum Rendern von 3D-Grafiken in Spielen verwendet und gibt die Strukturen für Meshes, Texturen, Animationen und benutzerdefinierte Objekte an. Es ist seit 2014 veraltet, da das Autodesk FBX-Dateiformat besser als moderneres Format dient. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/3d/x) . |

### Siehe auch

* class [FileType](../filetype)
* namensraum [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
