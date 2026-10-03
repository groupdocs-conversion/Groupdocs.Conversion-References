---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert 3D‑Dokumente. Enthält die folgenden Typen Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb Erfahren Sie mehr über 3D‑Formate hierhttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /de/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Definiert 3D‑Dokumente. Enthält die folgenden Typen: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) Erfahren Sie mehr über 3D‑Formate [hier](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Eine AMF-Datei besteht aus Richtlinien für die Objektbeschreibung, um in additiven Fertigungsprozessen verwendet zu werden. Sie enthält ein öffnendes XML-Tag und endet mit einem Element. Dies wird von einer XML-Deklarationszeile vorausgegangen, die die XML-Version und die Kodierung der Datei angibt. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Eine Datei mit der Erweiterung .ase ist ein Autodesk ASCII Scene Export-Dateiformat, das eine ASCII-Darstellung einer Szene ist und 2D‑ oder 3D‑Informationen enthält, während Szenendaten mit Autodesk exportiert werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Eine DAE-Datei ist ein Digital Asset Exchange‑Dateiformat, das zum Austausch von Daten zwischen interaktiven 3D‑Anwendungen verwendet wird. Dieses Dateiformat basiert auf dem COLLADA (COLLAborative Design Activity)‑XML‑Schema, einem offenen Standard‑XML‑Schema für den Austausch digitaler Assets zwischen Grafik‑Softwareanwendungen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Eine Datei mit der Erweiterung .drc ist ein komprimiertes 3D‑Dateiformat, das mit der Google‑Draco‑Bibliothek erstellt wurde. Google stellt Draco als Open‑Source‑Bibliothek zum Komprimieren und Dekomprimieren von 3D‑Geometriemeshes und Punktwolken bereit und verbessert die Speicherung und Übertragung von 3D‑Grafiken. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, ist ein beliebtes 3D‑Dateiformat, das ursprünglich von Kaydara für MotionBuilder entwickelt wurde. Es wurde 2006 von Autodesk Inc übernommen und ist heute eines der wichtigsten 3D‑Austauschformate, das von vielen 3D‑Werkzeugen verwendet wird. FBX ist sowohl im Binär‑ als auch im ASCII‑Dateiformat verfügbar. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB ist die binäre Dateiformatrepräsentation von 3D‑Modellen, die im GL Transmission Format (glTF) gespeichert werden. Dieses binäre Format speichert das glTF‑Asset (JSON, .bin und Bilder) in einem Binär‑Blob. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) ist ein 3D‑Dateiformat, das 3D‑Modellinformationen im JSON‑Format speichert. Die Verwendung von JSON reduziert sowohl die Größe von 3D‑Assets als auch die Laufzeitverarbeitung, die zum Entpacken und Verwenden dieser Assets erforderlich ist. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) ist ein effizientes, branchenorientiertes und flexibles, ISO‑standardisiertes 3D‑Datenformat, das von Siemens PLM Software entwickelt wurde. Die mechanischen CAD‑Bereiche Luft‑ und Raumfahrt, Automobilindustrie und schwere Geräte nutzen JT als ihr führendes 3D‑Visualisierungsformat. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | Eine Datei mit der Erweiterung .ma ist eine 3D‑Projektdatei, die mit der Autodesk‑Maya‑Anwendung erstellt wird. Sie enthält eine umfangreiche Liste von Textbefehlen, um Informationen über die Datei anzugeben. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | Eine Datei mit der Erweiterung .mb ist eine binäre Projektdatei, die mit der Autodesk‑Maya‑Anwendung erstellt wird. Im Gegensatz zum MA‑Dateiformat, das im ASCII‑Format vorliegt, werden MB‑Dateien im binären Dateiformat gespeichert. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ‑Dateien werden von der Wavefront‑Advanced‑Visualizer‑Anwendung verwendet, um geometrische Objekte zu definieren und zu speichern. Der rückwärts‑ und vorwärtsgerichtete Transfer geometrischer Daten wird durch OBJ‑Dateien ermöglicht. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, ist ein 3D‑Dateiformat, das grafische Objekte speichert, die als Sammlung von Polygonen beschrieben werden. Ziel dieses Dateiformats war es, einen einfachen und leicht zu handhabenden Dateityp zu schaffen, der allgemein genug ist, um für eine breite Palette von Modellen nützlich zu sein. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM‑Daten­dateien stehen in Zusammenhang mit AVEVA PDMS. Eine RVM‑Datei ist eine Projektdatei des AVEVA Plant Design Management System Model. Das Plant Design Management System (PDMS) von AVEVA ist das beliebteste 3D‑Designsystem, das datenzentrierte Technologie zur Projektverwaltung nutzt. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Eine Datei mit der Erweiterung .3ds stellt das 3D‑Studio‑(DOS‑)Mesh‑Dateiformat dar, das von Autodesk 3D Studio verwendet wird. Autodesk 3D Studio ist seit den 1990er‑Jahren auf dem Markt für 3D‑Dateiformate und hat sich inzwischen zu 3D Studio MAX weiterentwickelt, um mit 3D‑Modellierung, Animation und Rendering zu arbeiten. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, wird von Anwendungen verwendet, um 3D-Objektmodelle für eine Vielzahl anderer Anwendungen, Plattformen, Dienste und Drucker zu rendern. Es wurde entwickelt, um die Einschränkungen und Probleme anderer 3D-Dateiformate, wie STL, beim Arbeiten mit den neuesten Versionen von 3D-Druckern zu vermeiden. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) ist ein komprimiertes Dateiformat und Datenstruktur für 3D-Computergrafik. Es enthält 3D-Modellinformationen wie Dreiecksnetze, Beleuchtung, Schattierung, Bewegungsdaten, Linien und Punkte mit Farbe und Struktur. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Eine Datei mit der Erweiterung .usd ist ein Universal Scene Description-Dateiformat, das Daten zum Austausch und zur Ergänzung zwischen Anwendungen zur digitalen Inhaltserstellung codiert. Entwickelt von Pixar, ermöglicht USD den Austausch von elementaren Assets (wie Modellen) oder Animationen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Eine Datei mit .usdz ist ein unkomprimiertes und unverschlüsseltes ZIP-Archiv für das USD (Universal Scene Description)-Dateiformat, das Dateien anderer Formate (wie Texturen und Animationen) enthält und als Proxy dient, die im Archiv eingebettet sind und sie direkt mit der USD-Laufzeit ausführt, ohne dass ein Entpacken erforderlich ist. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Die Virtual Reality Modeling Language (VRML) ist ein Dateiformat zur Darstellung interaktiver 3D‑Weltobjekte im World Wide Web (www). Sie wird verwendet, um dreidimensionale Darstellungen komplexer Szenen wie Illustrationen, Definitionen und Virtual‑Reality‑Präsentationen zu erstellen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Eine Datei mit der Erweiterung .x bezieht sich auf das veraltete DirectX 3D Graphics‑Dateiformat, das mit Microsoft DirectX 2.0 eingeführt wurde. Es wurde für die 3D‑Grafikdarstellung in Spielen verwendet und definiert Strukturen für Netze, Texturen, Animationen und benutzerdefinierte Objekte. Es ist seit 2014 veraltet, da das Autodesk FBX‑Dateiformat als moderneres Format besser geeignet ist. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/3d/x). |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
