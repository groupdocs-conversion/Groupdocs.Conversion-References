---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Tabellenkalkulationsdokumente."
type: docs
weight: 25
url: /de/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

Definiert Tabellenkalkulationsdokumente. Enthält die folgenden Dateitypen:
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
Erfahren Sie mehr über Tabellenkalkulationsformate [hier](../https://wiki.fileformat.com/spreadsheet).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Xls](#Xls) | XLS stellt das Excel Binary File Format dar. |
|
|  | [Xlsx](#Xlsx) | XLSX ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. |
|
|  | [Xlsm](#Xlsm) | XLSM ist eine Art von Tabellenkalkulationsdateien, die Makros unterstützen. |
|
|  | [Xlsb](#Xlsb) | Das XLSB-Dateiformat definiert das Excel Binary File Format, das eine Sammlung von Datensätzen und Strukturen ist, die den Inhalt von Excel-Arbeitsmappen festlegen. |
|
|  | [Ods](#Ods) | Dateien mit der ODS-Erweiterung stehen für das OpenDocument Spreadsheet Document-Format, das vom Benutzer bearbeitet werden kann. |
|
|  | [Ots](#Ots) | Eine Datei mit der .ots-Erweiterung ist eine OpenDocument Spreadsheet Template-Datei, die mit der in Apache OpenOffice enthaltenen Calc-Anwendungssoftware erstellt wird. |
|
|  | [Xltx](#Xltx) | Die XLTX-Datei stellt ein Microsoft Excel Template dar, das auf den Spezifikationen des Office OpenXML-Dateiformats basiert. |
|
|  | [Xlt](#Xlt) | Dateien mit der .XLT-Erweiterung sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office‑Suite ist. |
|
|  | [Xltm](#Xltm) | Die XLTM-Dateierweiterung steht für Dateien, die von Microsoft Excel als makroaktivierte Vorlagendateien erzeugt werden. |
|
|  | [Tsv](#Tsv) | Ein Tab‑Separated Values (TSV)-Dateiformat stellt Daten dar, die in Klartextformat durch Tabulatoren getrennt sind. |
|
|  | [Xlam](#Xlam) | XLAM ist eine Makro‑aktivierte Add‑In‑Datei, die verwendet wird, um neue Funktionen zu Tabellenkalkulationen hinzuzufügen. |
|
|  | [Csv](#Csv) | Dateien mit der CSV‑Erweiterung (Comma Separated Values) stellen Klartextdateien dar, die Datensätze mit durch Kommas getrennten Werten enthalten. |
|
|  | [Fods](#Fods) | Eine Datei mit der .fods-Erweiterung ist ein Typ des OpenDocument Spreadsheet-Dokuments, das Daten in Zeilen und Spalten speichert. |
|
|  | [Dif](#Dif) | DIF steht für Data Interchange Format, das zum Import/Export von Tabellenkalkulationsdaten zwischen verschiedenen Anwendungen verwendet wird. |
|
|  | [Sxc](#Sxc) | Das Dateiformat SXC (Sun XML Calc) gehört zu einer Office‑Suite namens OpenOffice.org. |
|
|  | [Numbers](#Numbers) | Die Dateien mit der Erweiterung .numbers werden als Tabellenkalkulationsdateityp klassifiziert, deshalb ähneln sie den .xlsx‑Dateien; die Numbers‑Dateien werden jedoch mit der Apple iWork Numbers‑Tabellenkalkulationssoftware erstellt. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


Serialisierungskonstruktor


### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS steht für das Excel Binary File Format. Solche Dateien können von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xls).


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xlsx).


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM ist eine Art von Tabellenkalkulationsdateien, die Makros unterstützen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xlsm).


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


Das XLSB-Dateiformat definiert das Excel Binary File Format, das eine Sammlung von Datensätzen und Strukturen ist, die den Inhalt von Excel-Arbeitsmappen festlegen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xlsb).


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


Dateien mit der Erweiterung ODS stehen für das OpenDocument Spreadsheet Document‑Format, das vom Benutzer bearbeitet werden kann. Daten werden in der ODF‑Datei in Zeilen und Spalten gespeichert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/ods).


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


Eine Datei mit der Erweiterung .ots ist eine OpenDocument Spreadsheet‑Vorlagendatei, die mit der im Apache OpenOffice enthaltenen Calc‑Anwendung erstellt wird. Die Calc‑Anwendung ist ähnlich zu Excel, das in Microsoft Office verfügbar ist.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/ots).


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


Die XLTX‑Datei stellt eine Microsoft Excel‑Vorlage dar, die auf den Spezifikationen des Office OpenXML‑Dateiformats basiert. Sie wird verwendet, um eine Standardvorlagendatei zu erstellen, die zur Erzeugung von XLSX‑Dateien genutzt werden kann, die dieselben Einstellungen wie in der XLTX‑Datei aufweisen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xltx).


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


Dateien mit der Erweiterung .XLT sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft‑Office‑Suite ist. Microsoft Office 97‑2003 unterstützte das Erstellen neuer XLT‑Dateien sowie das Öffnen dieser.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xlt).


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


Die Dateierweiterung XLTM steht für Dateien, die von Microsoft Excel als makroaktivierte Vorlagendateien erzeugt werden. XLTM‑Dateien ähneln XLTX‑Dateien in ihrer Struktur, wobei letztere keine Vorlagendateien mit Makros unterstützen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xltm).


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Ein Tab‑Separated Values (TSV)-Dateiformat stellt Daten dar, die in Klartextformat durch Tabulatoren getrennt sind.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/tsv).


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM ist eine makroaktivierte Add‑In‑Datei, die verwendet wird, um neue Funktionen zu Tabellenkalkulationen hinzuzufügen. Ein Add‑In ist ein ergänzendes Programm, das zusätzlichen Code ausführt und zusätzliche Funktionalität für Tabellenkalkulationen bereitstellt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


Dateien mit der CSV‑Erweiterung (Comma Separated Values) stellen Klartextdateien dar, die Datensätze mit durch Kommas getrennten Werten enthalten.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/csv).


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


Eine Datei mit der Erweiterung .fods ist ein Typ des OpenDocument Spreadsheet-Dokumentformats, das Daten in Zeilen und Spalten speichert. Das Format ist Teil der ODF‑1.2‑Spezifikationen, die von OASIS veröffentlicht und gepflegt werden. Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/fods).


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF steht für Data Interchange Format und wird verwendet, um Tabellendaten zwischen verschiedenen Anwendungen zu importieren/exportieren. Dazu gehören Microsoft Excel, OpenOffice Calc, StarCalc und viele andere. Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/dif).


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


Das Dateiformat SXC (Sun XML Calc) gehört zu einer Office‑Suite namens OpenOffice.org. Dieses Format deckt im Allgemeinen die Tabellenkalkulationsbedürfnisse der Benutzer ab, da es ein XML‑basiertes Tabellenkalkulationsdateiformat ist. Das SXC‑Format unterstützt Formeln, Funktionen, Makros und Diagramme sowie DataPilot. Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/sxc).


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


Dateien mit der Erweiterung .numbers werden als Tabellenkalkulationsdateien klassifiziert, weshalb sie den .xlsx‑Dateien ähneln; die Numbers‑Dateien werden jedoch mit der Apple iWork Numbers‑Tabellenkalkulationssoftware erstellt. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/spreadsheet/numbers).


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
