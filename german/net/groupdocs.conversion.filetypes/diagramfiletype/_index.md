---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert Diagramm‑Dokumente. Enthält die folgenden Typen Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /de/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Definiert Diagrammdokumente. Enthält die folgenden Typen: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | Eine Datei mit der DRAWIO-Erweiterung ist ein Diagramm, das mit diagrams.net (früher draw.io) erstellt wurde. Sie wird im XML-Dateiformat mit dem mxfile-Stammelement gespeichert und enthält den Inhalt und die Formatierung der Diagrammelemente wie Text, Bilder, Layout, Formen und Positionierung. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | Eine Datei mit der MMD-Erweiterung ist ein Diagramm, das in der Mermaid-Markup-Sprache geschrieben ist. Sie wird als Klartextdokument gespeichert, das mit der Diagrammdeklaration beginnt, z. B. flowchart oder sequenceDiagram, gefolgt von der Definition der Knoten und der Verbindungen zwischen ihnen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW ist das Visio Graphics Service-Dateiformat, das die für die Darstellung einer Webzeichnung erforderlichen Streams und Speicherbereiche festlegt. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Jede in Microsoft Visio erstellte Zeichnung oder Grafik, die im XML-Format gespeichert wird, hat die .VDX-Erweiterung. Eine Visio-Zeichnung im XML-Format wird in der Visio-Software erstellt, die von Microsoft entwickelt wurde. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD-Dateien sind Zeichnungen, die mit der Microsoft Visio-Anwendung erstellt wurden, um eine Vielzahl von grafischen Objekten und deren Verbindungen darzustellen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Dateien mit der VSDM-Erweiterung sind Zeichnungsdateien, die mit der Microsoft Visio-Anwendung erstellt wurden und Makros unterstützen. VSDM-Dateien sind OPC/XML-Zeichnungen, die VSDX ähneln, aber zusätzlich die Möglichkeit bieten, Makros beim Öffnen der Datei auszuführen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Dateien mit der .VSDX-Erweiterung repräsentieren das Microsoft Visio-Dateiformat, das ab Microsoft Office 2013 eingeführt wurde. Es wurde entwickelt, um das binäre Dateiformat .VSD zu ersetzen, das von früheren Versionen von Microsoft Visio unterstützt wird. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS sind Schablonendateien, die mit Microsoft Visio 2007 und früher erstellt wurden. Schablonendateien stellen Zeichenobjekte bereit, die in einer .VSD Visio-Zeichnung eingebunden werden können. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Dateien mit der .VSSM-Erweiterung sind Microsoft Visio-Schablonendateien, die Makros unterstützen. Eine VSSM-Datei ermöglicht beim Öffnen das Ausführen von Makros, um die gewünschte Formatierung und Platzierung von Formen in einem Diagramm zu erreichen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Dateien mit der .VSSX-Erweiterung sind Zeichenstempel, die mit Microsoft Visio 2013 und höher erstellt wurden. Das VSSX-Dateiformat kann mit Visio 2013 und höher geöffnet werden. Visio-Dateien sind bekannt für die Darstellung einer Vielzahl von Zeichnungselementen wie Sammlungen von Formen, Verbindern, Flussdiagrammen, Netzwerklayouts, UML-Diagrammen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Dateien mit der VST-Erweiterung sind Vektorbilddateien, die mit Microsoft Visio erstellt wurden und als Vorlage für die Erstellung weiterer Dateien dienen. Diese Vorlagendateien liegen im Binärformat vor und enthalten das Standardlayout sowie die Einstellungen, die für die Erstellung neuer Visio-Zeichnungen verwendet werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Dateien mit der VSTM-Erweiterung sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Im Gegensatz zu VSDX-Dateien können aus VSTM-Vorlagen erstellte Dateien Makros ausführen, die in Visual Basic for Applications (VBA)-Code entwickelt wurden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Dateien mit der VSTX-Erweiterung sind Zeichenvorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. Diese VSTX-Dateien bieten einen Ausgangspunkt für die Erstellung von Visio-Zeichnungen, die als .VSDX-Dateien gespeichert werden, mit Standardlayout und -einstellungen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Dateien mit der .VSX-Erweiterung beziehen sich auf Stempel, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. VSX-Dateien werden im XML-Format gespeichert und wurden bis Visio 2013 unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Eine Datei mit der VTX-Erweiterung ist eine Microsoft Visio-Zeichenvorlage, die im XML-Format auf der Festplatte gespeichert wird. Die Vorlage soll eine Datei mit Basiseinstellungen bereitstellen, die zur Erstellung mehrerer Visio-Dateien mit denselben Einstellungen verwendet werden kann. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vtx). |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
