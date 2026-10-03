---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Diagrammdokumente."
type: docs
weight: 13
url: /de/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Definiert Diagrammdokumente. Enthält die folgenden Typen:
[Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdw),
[Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdx),
[Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsd),
[Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdm),
[Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdx),
[Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vss),
[Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssm),
[Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssx),
[Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vst),
[Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstm),
[Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstx),
[Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsx),
[Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vtx).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Vsd](#Vsd) | VSD‑Dateien sind Zeichnungen, die mit der Microsoft Visio‑Anwendung erstellt wurden, um verschiedene grafische Objekte und deren Verbindungen darzustellen. |
|
|  | [Vsdx](#Vsdx) | Dateien mit der Erweiterung .VSDX stellen das Microsoft Visio‑Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. |
|
|  | [Vss](#Vss) | VSS sind Schablonendateien, die mit Microsoft Visio 2007 und früher erstellt wurden. |
|
|  | [Vst](#Vst) | Dateien mit der Erweiterung VST sind Vektor‑Bilddateien, die mit Microsoft Visio erstellt wurden und als Vorlage für die Erstellung weiterer Dateien dienen. |
|
|  | [Vsx](#Vsx) | Dateien mit der Erweiterung .VSX beziehen sich auf Schablonen, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. |
|
|  | [Vtx](#Vtx) | Eine Datei mit der Erweiterung VTX ist eine Microsoft Visio‑Zeichnungsvorlage, die im XML‑Dateiformat auf der Festplatte gespeichert wird. |
|
|  | [Vdw](#Vdw) | VDW ist das Visio Graphics Service‑Dateiformat, das die für die Darstellung einer Web‑Zeichnung erforderlichen Streams und Speicherbereiche spezifiziert. |
|
|  | [Vdx](#Vdx) | Jede in Microsoft Visio erstellte Zeichnung oder Grafik, die im XML‑Format gespeichert wird, hat die Erweiterung .VDX. |
|
|  | [Vssx](#Vssx) | Dateien mit der Erweiterung .VSSX sind Zeichnungsschablonen, die mit Microsoft Visio 2013 und höher erstellt wurden. |
|
|  | [Vstx](#Vstx) | Dateien mit der Erweiterung VSTX sind Zeichnungsvorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. |
|
|  | [Vsdm](#Vsdm) | Dateien mit der Erweiterung VSDM sind Zeichnungsdateien, die mit der Microsoft Visio‑Anwendung erstellt wurden und Makros unterstützen. |
|
|  | [Vssm](#Vssm) | Dateien mit der Erweiterung .VSSM sind Microsoft Visio Stencil-Dateien, die Unterstützung für Makros bieten. |
|
|  | [Vstm](#Vstm) | Dateien mit der Erweiterung VSTM sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Serialisierungskonstruktor


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


VSD‑Dateien sind Zeichnungen, die mit der Microsoft Visio‑Anwendung erstellt wurden, um verschiedene grafische Objekte und deren Verbindungen darzustellen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vsd).


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


Dateien mit der Erweiterung .VSDX stellen das Microsoft Visio-Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. Es wurde entwickelt, um das binäre Dateiformat .VSD zu ersetzen, das von früheren Versionen von Microsoft Visio unterstützt wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vsdx).


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS sind Stencil-Dateien, die mit Microsoft Visio 2007 und früher erstellt wurden. Stencil-Dateien stellen Zeichenobjekte bereit, die in einer .VSD Visio-Zeichnung eingebunden werden können.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vss).


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


Dateien mit der Erweiterung VST sind Vektorbilddateien, die mit Microsoft Visio erstellt wurden und als Vorlage für die Erstellung weiterer Dateien dienen. Diese Vorlagendateien liegen im binären Dateiformat vor und enthalten das Standardlayout sowie die Einstellungen, die für die Erstellung neuer Visio-Zeichnungen verwendet werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vst).


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


Dateien mit der Erweiterung .VSX beziehen sich auf Stencils, die aus Zeichnungen und Formen bestehen, die zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. VSX-Dateien werden im XML-Dateiformat gespeichert und wurden bis Visio 2013 unterstützt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vsx).


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


Eine Datei mit der Erweiterung VTX ist eine Microsoft Visio-Zeichnungsvorlage, die im XML-Dateiformat auf dem Datenträger gespeichert wird. Die Vorlage soll eine Datei mit Grundeinstellungen bereitstellen, die zur Erstellung mehrerer Visio-Dateien mit denselben Einstellungen verwendet werden kann.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vtx).


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW ist das Visio Graphics Service‑Dateiformat, das die für die Darstellung einer Web‑Zeichnung erforderlichen Streams und Speicherbereiche spezifiziert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/web/vdw).


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Alle in Microsoft Visio erstellten Zeichnungen oder Diagramme, die im XML-Format gespeichert werden, haben die Erweiterung .VDX. Eine Visio-Zeichnung im XML-Format wird in der Visio-Software erstellt, die von Microsoft entwickelt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vdx).


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


Dateien mit der Erweiterung .VSSX sind Zeichen-Stencils, die mit Microsoft Visio 2013 und höher erstellt wurden. Das VSSX-Dateiformat kann mit Visio 2013 und höher geöffnet werden. Visio-Dateien sind bekannt für die Darstellung einer Vielzahl von Zeichnungselementen wie einer Sammlung von Formen, Verbindern, Flussdiagrammen, Netzwerklayouts, UML-Diagrammen,
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vssx).


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


Dateien mit der Erweiterung VSTX sind Zeichenvorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. Diese VSTX-Dateien bieten einen Ausgangspunkt für die Erstellung von Visio-Zeichnungen, die als .VSDX-Dateien gespeichert werden, mit Standardlayout und -einstellungen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vstx).


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


Dateien mit der VSDM-Erweiterung sind Zeichen­dateien, die mit der Microsoft Visio‑Anwendung erstellt wurden und Makros unterstützen. VSDM‑Dateien sind OPC/XML‑Zeichnungen, die VSDX ähneln, aber zudem die Möglichkeit bieten, Makros auszuführen, wenn die Datei geöffnet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vsdm).


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


Dateien mit der .VSSM-Erweiterung sind Microsoft Visio‑Stencil‑Dateien, die Makros unterstützen. Eine VSSM‑Datei ermöglicht beim Öffnen das Ausführen von Makros, um die gewünschte Formatierung und Platzierung von Formen in einem Diagramm zu erreichen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vssm).


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


Dateien mit der VSTM-Erweiterung sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Im Gegensatz zu VSDX‑Dateien können Dateien, die aus VSTM‑Vorlagen erstellt wurden, Makros ausführen, die in Visual Basic for Applications (VBA)-Code entwickelt wurden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vstm).


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
