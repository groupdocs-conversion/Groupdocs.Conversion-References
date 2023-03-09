---
title: SpreadsheetFileType
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Definiert SpreadsheetDokumente. Enthält die folgenden Dateitypen Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . Erfahren Sie mehr über TabellenkalkulationsformateHierhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 1050
url: /de/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Definiert Spreadsheet-Dokumente. Enthält die folgenden Dateitypen: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Erfahren Sie mehr über Tabellenkalkulationsformate[Hier](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Serialisierungskonstruktor |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als Standard-Hash-Funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Zeichenfolgendarstellung |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Dateien mit der Erweiterung CSV (Comma Separated Values) stellen reine Textdateien dar, die Datensätze mit kommagetrennten Werten enthalten. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF steht für Data Interchange Format, das zum Importieren/Exportieren von Tabellenkalkulationsdaten zwischen verschiedenen Anwendungen verwendet wird. Dazu gehören Microsoft Excel, OpenOffice Calc, StarCalc und viele andere. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Eine Datei mit der Erweiterung .fods ist eine Art OpenDocument Spreadsheet-Dokumentformat, das Daten in Zeilen und Spalten speichert. Das Format ist als Teil der ODF 1.2-Spezifikationen spezifiziert, die von OASIS veröffentlicht und verwaltet werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/fods) . |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Die Dateien mit der Erweiterung .numbers werden als Tabellenkalkulationsdateityp klassifiziert, deshalb ähneln sie den .xlsx-Dateien; Die Numbers-Dateien werden jedoch mithilfe der Tabellenkalkulationssoftware Apple iWork Numbers erstellt. Weitere Informationen zu diesem Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Dateien mit der ODS-Erweiterung stehen für OpenDocument Spreadsheet Document-Format, das vom Benutzer bearbeitet werden kann. Daten werden in der ODF-Datei in Zeilen und Spalten gespeichert. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Eine Datei mit der Erweiterung .ots ist eine OpenDocument-Tabellenvorlagendatei, die mit der in Apache OpenOffice enthaltenen Calc-Anwendungssoftware erstellt wird. Die Calc-Anwendungssoftware ähnelt Excel, das in Microsoft Office verfügbar ist. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/ots) . |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Das Dateiformat SXC (Sun XML Calc) gehört zu einer Office-Suite namens OpenOffice.org. Dieses Format befasst sich im Allgemeinen mit den Tabellenkalkulationsanforderungen der Benutzer, da es sich um ein XML-basiertes Tabellenkalkulationsdateiformat handelt. Das SXC-Format unterstützt Formeln, Funktionen, Makros und Diagramme zusammen mit DataPilot. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/sxc) . |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Ein TSV-Dateiformat (Tab-Separated Values) stellt durch Tabulatoren getrennte Daten im Nur-Text-Format dar. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM ist eine makrofähige Add-In-Datei, die verwendet wird, um neue Funktionen zu Tabellenkalkulationen hinzuzufügen. Ein Add-In ist ein Zusatzprogramm, das zusätzlichen Code ausführt und zusätzliche Funktionen für Tabellenkalkulationen bereitstellt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/xlam/) . |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS steht für Excel Binary File Format. Solche Dateien können von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Das XLSB-Dateiformat gibt das Excel-Binärdateiformat an, bei dem es sich um eine Sammlung von Datensätzen und Strukturen handelt, die den Inhalt von Excel-Arbeitsmappen angeben. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM ist eine Art Tabellenkalkulationsdatei, die Makros unterstützt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Dateien mit der Erweiterung .XLT sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office-Suite ist. Microsoft Office 97-2003 unterstützte das Erstellen neuer XLT-Dateien sowie das Öffnen dieser. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | Die XLTM-Dateierweiterung stellt Dateien dar, die von Microsoft Excel als makrofähige Vorlagendateien generiert werden. XLTM-Dateien ähneln XLTX in ihrer Struktur, abgesehen davon, dass letztere das Erstellen von Vorlagendateien mit Makros nicht unterstützen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX-Datei stellt eine Microsoft Excel-Vorlage dar, die auf den Office OpenXML-Dateiformatspezifikationen basiert. Es wird verwendet, um eine Standardvorlagendatei zu erstellen, die zum Generieren von XLSX-Dateien verwendet werden kann, die dieselben Einstellungen wie in der XLTX-Datei angegeben aufweisen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xltx) . |

### Siehe auch

* class [FileType](../filetype)
* namensraum [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
