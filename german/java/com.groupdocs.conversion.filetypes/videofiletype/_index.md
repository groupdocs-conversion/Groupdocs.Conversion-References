---
title: "VideoFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Videodokumente. Enthält die folgenden Typen. Erfahren Sie mehr über Videoformate hier."
type: docs
weight: 26
url: /de/java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Definiert Videodokumente. Enthält die folgenden Typen: , , , , , , , Erfahren Sie mehr über Videoformate [hier](../https://docs.fileformat.com/video/).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [VideoFileType()](#VideoFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Mp4](#Mp4) | MP4 (Kurzform für MPEG‑4 Part 14) ist ein Dateiformat, das auf ISO/IEC 14496‑12:2004 basiert und auf dem QuickTime‑Dateiformat beruht, jedoch formell die Unterstützung von Initial Object Descriptors (IOD) und anderen MPEG‑Funktionen spezifiziert. |
|
|  | [Avi](#Avi) | Das AVI‑Dateiformat ist ein Audio‑Video‑Multimedia‑Container‑Dateiformat, das von Microsoft eingeführt wurde. |
|
|  | [Flv](#Flv) | FLV (Flash Video) ist ein Container‑Dateiformat mit der .flv‑Erweiterung. |
|
|  | [Mkv](#Mkv) | MKV (Matroska Video) ist ein Multimedia‑Container, ähnlich dem MOV‑ und AVI‑Format, unterstützt jedoch mehr als eine Audio‑ und Untertitelspur in derselben Datei. |
|
|  | [Mov](#Mov) | MOV oder das QuickTime‑Dateiformat ist ein von Apple entwickelter Multimedia‑Container: er enthält einen oder mehrere Tracks, wobei jeder Track einen bestimmten Datentyp enthält, d. h. |
|
|  | [Webm](#Webm) | Eine Datei mit der .webm‑Erweiterung ist eine Videodatei, die auf dem offenen, lizenzfreien WebM‑Dateiformat basiert. |
|
|  | [Wmv](#Wmv) | Windows Media Video ist das von Microsoft entwickelte komprimierte Videoformat. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Serialisierungskonstruktor


### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (Kurzform für MPEG‑4 Part 14) ist ein Dateiformat, das auf ISO/IEC 14496‑12:2004 basiert und auf dem QuickTime‑Dateiformat beruht, jedoch formell die Unterstützung von Initial Object Descriptors (IOD) und anderen MPEG‑Funktionen spezifiziert. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/video/mp4/).


### Avi {#Avi}
```
public static final VideoFileType Avi
```


Das AVI‑Dateiformat ist ein Audio‑Video‑Multimedia‑Container‑Dateiformat, das von Microsoft eingeführt wurde. Es enthält die Audio‑ und Videodaten, die mit mehreren Codecs (Coder/Decoder) wie XVid und DivX erstellt und komprimiert wurden. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/video/avi/).


### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) ist ein Container‑Dateiformat mit der .flv‑Erweiterung. FLV wird verwendet, um Audio‑/Video‑Inhalte über das Internet mithilfe des Adobe Flash Player oder Adobe Air zu liefern. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/video/flv/).


### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) ist ein Multimedia-Container, ähnlich dem MOV- und AVI-Format, unterstützt jedoch mehr als eine Audio‑ und Untertitelspur in derselben Datei. Eine MKV‑Datei ist das Matroska‑Multimedia‑Containerformat, das für Video verwendet wird. Erfahren Sie mehr über dieses Dateiformat [here](../https://docs.fileformat.com/video/mkv/).


### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV oder QuickTime-Dateiformat ist ein Multimedia-Container, der von Apple entwickelt wurde: enthält einen oder mehrere Tracks, wobei jeder Track einen bestimmten Datentyp wie Video, Audio, Text usw. enthält. Erfahren Sie mehr über dieses Dateiformat [here](../https://docs.fileformat.com/video/mov/).


### Webm {#Webm}
```
public static final VideoFileType Webm
```


Eine Datei mit der Erweiterung .webm ist eine Videodatei, die auf dem offenen, lizenzfreien WebM-Dateiformat basiert. Sie wurde für das Teilen von Videos im Web entwickelt und definiert die Containerstruktur einschließlich Video‑ und Audioformate. Erfahren Sie mehr über dieses Dateiformat [here](../https://docs.fileformat.com/video/webm//).


### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video ist das von Microsoft entwickelte komprimierte Videoformat. Nach der Standardisierung durch die Society of Motion Picture and Television Engineers (SMPTE) gilt WMV nun als offenes Standardformat. Erfahren Sie mehr über dieses Dateiformat [here](../https://docs.fileformat.com/video/wmv/).


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
