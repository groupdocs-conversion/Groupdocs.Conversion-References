---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Präsentationsdateiformate, die eine Sammlung von Datensätzen speichern, um Präsentationsdaten wie Folien, Formen, Text, Animationen, Video, Audio und eingebettete Objekte zu enthalten."
type: docs
weight: 22
url: /de/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Definiert Präsentationsdateiformate, die eine Sammlung von Datensätzen speichern, um Präsentationsdaten wie Folien, Formen, Text, Animationen, Video, Audio und eingebettete Objekte zu enthalten.
Enthält die folgenden Dateitypen:
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
Erfahren Sie mehr über Präsentationsformate [hier](../https://wiki.fileformat.com/presentation).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Ppt](#Ppt) | Eine Datei mit der Erweiterung PPT stellt eine PowerPoint‑Datei dar, die aus einer Sammlung von Folien für die Anzeige als Diashow besteht. |
|
|  | [Pps](#Pps) | PPS‑Dateien (PowerPoint Slide Show) werden mit Microsoft PowerPoint für Diashow‑Zwecke erstellt. |
|
|  | [Pptx](#Pptx) | Dateien mit der Erweiterung PPTX sind Präsentationsdateien, die mit der beliebten Microsoft‑PowerPoint‑Anwendung erstellt wurden. |
|
|  | [Ppsx](#Ppsx) | PPSX‑Dateien (PowerPoint Slide Show) werden mit Microsoft PowerPoint 2007 und höher für Diashow‑Zwecke erstellt. |
|
|  | [Odp](#Odp) | Dateien mit der Erweiterung ODP stellen ein Präsentationsdateiformat dar, das von OpenOffice.org im OASIS‑Open‑Standard verwendet wird. |
|
|  | [Otp](#Otp) | Dateien mit der Erweiterung .OTP stellen Präsentationsvorlagendateien dar, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt werden. |
|
|  | [Potx](#Potx) | Dateien mit der Erweiterung .POTX stellen Microsoft PowerPoint-Vortragsvorlagen dar, die mit Microsoft PowerPoint 2007 und höher erstellt werden. |
|
|  | [Pot](#Pot) | Dateien mit der Erweiterung .POT stellen Microsoft PowerPoint-Vorlagendateien dar, die von PowerPoint‑Versionen 97‑2003 erstellt wurden. |
|
|  | [Potm](#Potm) | Dateien mit der Erweiterung POTM sind Microsoft PowerPoint-Vorlagendateien mit Unterstützung für Makros. |
|
|  | [Pptm](#Pptm) | Dateien mit der Erweiterung PPTM sind makrofähige Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder neueren Versionen erstellt werden. |
|
|  | [Ppsm](#Ppsm) | Dateien mit der Erweiterung PPSM stellen ein makrofähiges Diashow-Dateiformat dar, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde. |
|
|  | [Fodp](#Fodp) | Dateien mit der Erweiterung FODP stellen eine OpenDocument Flat XML-Präsentation dar. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Serialisierungskonstruktor


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


Eine Datei mit der Erweiterung PPT stellt eine PowerPoint‑Datei dar, die aus einer Sammlung von Folien für die Anzeige als Diashow besteht. Sie gibt das von Microsoft PowerPoint 97‑2003 verwendete Binärdateiformat an.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/ppt).


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint‑Diashow, Dateien werden mit Microsoft PowerPoint für Diashow‑Zwecke erstellt. Das Lesen und Erstellen von PPS‑Dateien wird von Microsoft PowerPoint 97‑2003 unterstützt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/pps).


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


Dateien mit der Erweiterung PPTX sind Präsentationsdateien, die mit der beliebten Microsoft PowerPoint‑Anwendung erstellt werden. Im Gegensatz zur vorherigen Version des Präsentationsdateiformats PPT, das binär war, basiert das PPTX‑Format auf dem Microsoft PowerPoint Open XML‑Präsentationsdateiformat.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/pptx).


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX‑Dateien (PowerPoint Slide Show) werden mit Microsoft PowerPoint 2007 und höher für Diashow‑Zwecke erstellt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/ppsx).


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


Dateien mit der Erweiterung ODP stellen ein Präsentationsdateiformat dar, das von OpenOffice.org im OASIS‑Open‑Standard verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/odp).


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


Dateien mit der Erweiterung .OTP stellen Präsentationsvorlagendateien dar, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/otp).


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


Dateien mit der Erweiterung .POTX stellen Microsoft PowerPoint-Vortragsvorlagen dar, die mit Microsoft PowerPoint 2007 und höher erstellt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/potx).


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


Dateien mit der Erweiterung .POT stellen Microsoft PowerPoint-Vorlagendateien dar, die von PowerPoint‑Versionen 97‑2003 erstellt wurden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/pot).


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


Dateien mit der Erweiterung POTM sind Microsoft PowerPoint-Vorlagendateien mit Unterstützung für Makros. POTM‑Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standardeinstellungen, die zur Erstellung weiterer Präsentationsdateien verwendet werden können.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/potm).


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


Dateien mit der Erweiterung PPTM sind makrofähige Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder neueren Versionen erstellt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/pptm).


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


Dateien mit der Erweiterung PPSM stellen ein makrofähiges Diashow-Dateiformat dar, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/ppsm).


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


Dateien mit der Erweiterung FODP stellen eine OpenDocument Flat XML‑Präsentation dar. Die Präsentationsdatei wird im OpenDocument‑Format gespeichert, jedoch mit einem flachen XML‑Format anstelle des .ZIP‑Containers, der von Standard‑ .ODP‑Dateien verwendet wird.


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
