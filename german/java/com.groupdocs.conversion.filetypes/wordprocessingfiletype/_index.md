---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Textverarbeitungsdateien, die Benutzerinformationen im Nur-Text- oder Rich-Text-Format enthalten."
type: docs
weight: 28
url: /de/java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Definiert Textverarbeitungsdateien, die Benutzerinformationen im Klartext oder Rich‑Text‑Format enthalten. Ein Klartext‑Dateiformat enthält unformatierten Text und es können keine Schrift‑ oder Seiteneinstellungen usw. angewendet werden. Im Gegensatz dazu ermöglicht ein Rich‑Text‑Dateiformat Formatierungsoptionen wie das Festlegen von Schriftarten, Stilen (fett, kursiv, unterstrichen usw.), Seitenrändern, Überschriften, Aufzählungen und Nummerierungen sowie mehrere andere Formatierungsfunktionen.
Enthält die folgenden Dateitypen:
[Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Doc),
[Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docm),
[Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docx),
[Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dot),
[Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotm),
[Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotx),
[Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Odt),
[Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Ott),
[Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Rtf),
[Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Txt),
[Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Md),
Erfahren Sie mehr über Textverarbeitungsformate [hier](../https://wiki.fileformat.com/word-processing).


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingFileType()](#WordProcessingFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Doc](#Doc) | Dateien mit der Erweiterung .doc stellen Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärdateiformat erzeugt werden. |
|
|  | [Docm](#Docm) | DOCM-Dateien sind von Microsoft Word 2007 oder höher erzeugte Dokumente mit der Möglichkeit, Makros auszuführen. |
|
|  | [Docx](#Docx) | DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. |
|
|  | [Dot](#Dot) | Dateien mit der Erweiterung .DOT sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOC‑ oder DOCX‑Dateien zu haben. |
|
|  | [Dotm](#Dotm) | Eine Datei mit der Erweiterung DOTM stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. |
|
|  | [Dotx](#Dotx) | Dateien mit der Erweiterung DOTX sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOCX‑Dateien zu haben. |
|
|  | [Rtf](#Rtf) | Eingeführt und dokumentiert von Microsoft, stellt das Rich Text Format (RTF) eine Methode zur Codierung von formatiertem Text und Grafiken für die Verwendung in Anwendungen dar. |
|
|  | [Odt](#Odt) | ODT-Dateien sind eine Art von Dokumenten, die mit Textverarbeitungsprogrammen erstellt werden und auf dem OpenDocument‑Textdateiformat basieren. |
|
|  | [Ott](#Ott) | Dateien mit der Erweiterung .OTT stellen Vorlagendokumente dar, die von Anwendungen gemäß dem OpenDocument‑Standardformat von OASIS erzeugt werden. |
|
|  | [Txt](#Txt) | Eine Datei mit der Erweiterung .TXT stellt ein Textdokument dar, das Klartext in Form von Zeilen enthält. |
|
|  | [Md](#Md) | Textdateien, die mit Markdown‑Sprachdialekten erstellt wurden, werden mit der Dateierweiterung .MD oder .MARKDOWN gespeichert. |
|
|  | [Ml](#Ml) | Ml file |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


Serialisierungskonstruktor


### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


Dateien mit der Erweiterung .doc stellen Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärdateiformat erzeugt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/doc).


### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


DOCM-Dateien sind von Microsoft Word 2007 oder höher erzeugte Dokumente mit der Möglichkeit, Makros auszuführen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/docm).


### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX ist ein weit verbreitetes Format für Microsoft‑Word‑Dokumente. Eingeführt ab 2007 mit der Veröffentlichung von Microsoft Office 2007, wurde die Struktur dieses neuen Dokumentformats von rein binär zu einer Kombination aus XML‑ und Binärdateien geändert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/docx).


### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


Dateien mit der Erweiterung .DOT sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOC‑ oder DOCX‑Dateien zu haben.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/dot).


### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


Eine Datei mit der Erweiterung DOTM stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/dotm).


### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


Dateien mit der Erweiterung DOTX sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOCX‑Dateien zu haben.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/dotx).


### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Eingeführt und dokumentiert von Microsoft, stellt das Rich Text Format (RTF) eine Methode zur Codierung von formatiertem Text und Grafiken für die Verwendung in Anwendungen dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/rtf).


### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ODT-Dateien sind eine Art von Dokumenten, die mit Textverarbeitungsprogrammen erstellt werden und auf dem OpenDocument‑Textdateiformat basieren.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/odt).


### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


Dateien mit der Erweiterung .OTT stellen Vorlagendokumente dar, die von Anwendungen gemäß dem OpenDocument‑Standardformat von OASIS erzeugt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/ott).


### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


Eine Datei mit der Erweiterung .TXT stellt ein Textdokument dar, das Klartext in Form von Zeilen enthält.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/txt).


### Md {#Md}
```
public static final WordProcessingFileType Md
```


Textdateien, die mit Markdown‑Sprachdialekten erstellt wurden, werden mit der Dateierweiterung .MD oder .MARKDOWN gespeichert. MD‑Dateien werden im Klartextformat abgelegt, das die Markdown‑Sprache verwendet und zudem Inline‑Textsymbole enthält, die festlegen, wie ein Text formatiert werden kann, z. B. Einrückungen, Tabellenformatierung, Schriftarten und Überschriften. Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/md).


### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Ml file


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Standard‑Ladeoptionen für den Quelldateityp vorbereitet


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
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
