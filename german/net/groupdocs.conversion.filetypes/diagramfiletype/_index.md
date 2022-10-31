---
title: DiagramFileType
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Definiert Diagrammdokumente. Enthält die folgenden Typen Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx .
type: docs
weight: 830
url: /de/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Definiert Diagrammdokumente. Enthält die folgenden Typen: [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx) .

```csharp
public sealed class DiagramFileType : FileType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW ist das Dateiformat des Visio Graphics Service, das die zum Rendern einer Webzeichnung erforderlichen Streams und Speicher angibt. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Alle Zeichnungen oder Diagramme, die in Microsoft Visio erstellt, aber im XML-Format gespeichert wurden, haben die Erweiterung .VDX. Eine Visio-Zeichnungs-XML-Datei wird in der von Microsoft entwickelten Visio-Software erstellt. Weitere Informationen zu diesem Dateiformat[hier](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD-Dateien sind Zeichnungen, die mit der Microsoft Visio-Anwendung erstellt wurden, um eine Vielzahl von grafischen Objekten und die Verbindung zwischen diesen darzustellen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Dateien mit der Erweiterung VSDM sind Zeichnungsdateien, die mit der Microsoft Visio-Anwendung erstellt wurden, die Makros unterstützt. VSDM-Dateien sind OPC/XML-Zeichnungen, die VSDX ähneln, aber auch die Möglichkeit bieten, Makros auszuführen, wenn die Datei geöffnet wird. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Dateien mit der Erweiterung .VSDX stellen das Microsoft Visio-Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. Es wurde entwickelt, um das binäre Dateiformat .VSD zu ersetzen, das von früheren Versionen von Microsoft Visio unterstützt wird. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS sind Schablonendateien, die mit Microsoft Visio 2007 und früher erstellt wurden. Schablonendateien stellen Zeichnungsobjekte bereit, die in eine VSD-Visio-Zeichnung eingefügt werden können. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vss) . |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Dateien mit der Erweiterung .VSSM sind Microsoft Visio-Schablonendateien, die Unterstützung für Makros bieten. Wenn eine VSSM-Datei geöffnet wird, können Makros ausgeführt werden, um die gewünschte Formatierung und Platzierung von Formen in einem Diagramm zu erreichen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vssm) . |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Dateien mit der Erweiterung .VSSX sind Zeichnungsschablonen, die mit Microsoft Visio 2013 und höher erstellt wurden. Das VSSX-Dateiformat kann mit Visio 2013 und höher geöffnet werden. Visio-Dateien sind für die Darstellung einer Vielzahl von Zeichnungselementen bekannt, z. B. Sammlung von Formen, Konnektoren, Flussdiagramme, Netzwerklayout, UML-Diagramme, . Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vssx) . |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Dateien mit der Endung VST sind Vektorbilddateien, die mit Microsoft Visio erstellt wurden und als Vorlage für die Erstellung weiterer Dateien dienen. Diese Vorlagendateien liegen im binären Dateiformat vor und enthalten das Standardlayout und die Standardeinstellungen, die zum Erstellen neuer Visio-Zeichnungen verwendet werden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vst) . |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Dateien mit der Erweiterung VSTM sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Im Gegensatz zu VSDX-Dateien können aus VSTM-Vorlagen erstellte Dateien Makros ausführen, die in VBA-Code (Visual Basic for Applications) entwickelt wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vstm) . |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Dateien mit VSTX-Erweiterungen sind Zeichnungsvorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. Diese VSTX-Dateien bieten einen Ausgangspunkt zum Erstellen von Visio-Zeichnungen, die als VSDX-Dateien mit Standardlayout und Standardeinstellungen gespeichert werden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vstx) . |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Dateien mit der Erweiterung .VSX beziehen sich auf Schablonen, die aus Zeichnungen und Formen bestehen, die zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. VSX-Dateien werden im XML-Dateiformat gespeichert und wurden bis Visio 2013 unterstützt. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vsx) . |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Eine Datei mit der Erweiterung VTX ist eine Microsoft Visio-Zeichnungsvorlage, die im XML-Dateiformat auf einem Datenträger gespeichert wird. Die Vorlage soll eine Datei mit Grundeinstellungen bereitstellen, die zum Erstellen mehrerer Visio-Dateien mit denselben Einstellungen verwendet werden kann. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vtx) . |

### Siehe auch

* class [FileType](../filetype)
* namensraum [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
