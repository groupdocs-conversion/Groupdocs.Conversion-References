---
title: "FontFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Schriftartdokumente."
type: docs
weight: 17
url: /de/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Definiert Schriftartdokumente.
Enthält die folgenden Typen:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
Erfahren Sie mehr über Schriftformate [hier](../https://wiki.fileformat.com/font).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Ttf](#Ttf) | Eine Datei mit der Erweiterung .ttf stellt Schriftdateien dar, die auf der TrueType-Spezifikationsschrifttechnologie basieren. |
|
|  | [Eot](#Eot) | Eine Datei mit der Erweiterung .eot ist eine OpenType-Schrift, die in ein Dokument eingebettet ist. |
|
|  | [Otf](#Otf) | Eine Datei mit der Erweiterung .otf bezieht sich auf das OpenType-Schriftformat. |
|
|  | [Cff](#Cff) | Eine Datei mit der Erweiterung .cff ist ein Compact Font Format und ist auch als PostScript Type 1 oder CIDFont bekannt. |
|
|  | [Type1](#Type1) | Type‑1-Schriften sind eine veraltete Adobe‑Technologie, die in Desktop‑Publishing‑Software und Druckern, die PostScript verwenden konnten, weit verbreitet war. |
|
|  | [Woff](#Woff) | Eine Datei mit der Erweiterung .woff ist eine Web‑Schriftdatei, die auf dem Web Open Font Format (WOFF) basiert. |
|
|  | [Woff2](#Woff2) | Eine Datei mit der Erweiterung .woff ist eine Web‑Schriftdatei, die auf dem Web Open Font Format (WOFF) basiert. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Serialisierungskonstruktor


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


Eine Datei mit der Erweiterung .ttf stellt Schriftdateien dar, die auf der TrueType‑Spezifikationsschrifttechnologie basieren. Sie wurde ursprünglich von Apple Computer, Inc. für Mac OS entwickelt und veröffentlicht und später von Microsoft für Windows OS übernommen. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


Eine Datei mit der Erweiterung .eot ist eine OpenType‑Schrift, die in ein Dokument eingebettet ist. Diese werden hauptsächlich in Webdateien wie einer Webseite verwendet. Sie wurde von Microsoft erstellt und wird von Microsoft‑Produkten, einschließlich PowerPoint‑Präsentationen im .pps‑Format, unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


Eine Datei mit der Erweiterung .otf bezieht sich auf das OpenType‑Schriftformat. Das OTF‑Schriftformat ist skalierbarer und erweitert die bestehenden Funktionen der TTF‑Formate für digitale Typografie. Entwickelt von Microsoft und Adobe, kombiniert OTF die Merkmale von PostScript‑ und TrueType‑Schriftformaten. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


Eine Datei mit der Erweiterung .cff ist ein Compact Font Format und ist auch als PostScript Type 1 oder CIDFont bekannt. CFF dient als Container, um mehrere Schriften zusammen in einer einzigen Einheit, dem FontSet, zu speichern. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type‑1‑Schriften sind eine veraltete Adobe‑Technologie, die in Desktop‑Publishing‑Software und Druckern, die PostScript verwenden konnten, weit verbreitet war. Obwohl Type‑1‑Schriften auf vielen modernen Plattformen, Webbrowsern und mobilen Betriebssystemen nicht unterstützt werden, werden sie in einigen Betriebssystemen noch unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


Eine Datei mit der Erweiterung .woff ist eine Web‑Schriftdatei, die auf dem Web Open Font Format (WOFF) basiert. Sie enthält einen format‑spezifischen komprimierten Container, der entweder auf TrueType (.TTF) oder OpenType (.OTT) Schriftarten basiert. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


Eine Datei mit der Erweiterung .woff ist eine Web‑Schriftdatei, die auf dem Web Open Font Format (WOFF) basiert. Sie enthält einen format‑spezifischen komprimierten Container, der entweder auf TrueType (.TTF) oder OpenType (.OTT) Schriftarten basiert. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/font/woff/).


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
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
