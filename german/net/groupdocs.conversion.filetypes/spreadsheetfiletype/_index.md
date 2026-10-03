---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert Tabellenkalkulationsdokumente. Enthält die folgenden Dateitypen Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. Erfahren Sie mehr über Tabellenkalkulationsformate herehttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /de/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Definiert Tabellenkalkulationsdokumente. Enthält die folgenden Dateitypen: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Erfahren Sie mehr über Tabellenkalkulationsformate [here](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Dateien mit der Erweiterung CSV (Comma Separated Values) sind Textdateien, die Datensätze mit kommagetrennten Werten enthalten. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF steht für Data Interchange Format und wird verwendet, um Tabellendaten zwischen verschiedenen Anwendungen zu importieren/exportieren. Dazu gehören Microsoft Excel, OpenOffice Calc, StarCalc und viele andere. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel ist Office Open XML SpreadsheetML, das in einer flachen XML-Datei anstelle eines ZIP-Pakets gespeichert wird. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Eine Datei mit der Erweiterung .fods ist ein Typ des OpenDocument Spreadsheet-Dokuments, das Daten in Zeilen und Spalten speichert. Das Format ist Teil der ODF 1.2-Spezifikationen, die von OASIS veröffentlicht und gepflegt werden. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Dateien mit der Erweiterung .numbers werden als Tabellenkalkulationsdateien klassifiziert, weshalb sie den .xlsx-Dateien ähneln; die Numbers-Dateien werden jedoch mit der Apple iWork Numbers-Tabellenkalkulationssoftware erstellt. Erfahren Sie mehr über dieses Dateiformat [here](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Dateien mit der ODS-Erweiterung stehen für das OpenDocument Spreadsheet Document-Format, das vom Benutzer bearbeitet werden kann. Daten werden in der ODF-Datei in Zeilen und Spalten gespeichert. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Eine Datei mit der .ots-Erweiterung ist eine OpenDocument Spreadsheet Template‑Datei, die mit der in Apache OpenOffice enthaltenen Calc‑Anwendung erstellt wird. Die Calc‑Anwendung ist ähnlich zu Excel, das in Microsoft Office verfügbar ist. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Das Dateiformat SXC (Sun XML Calc) gehört zu einer Office‑Suite namens OpenOffice.org. Dieses Format deckt im Allgemeinen die Tabellenkalkulationsbedürfnisse der Benutzer ab, da es ein XML‑basiertes Tabellenkalkulationsdateiformat ist. Das SXC‑Format unterstützt Formeln, Funktionen, Makros und Diagramme sowie DataPilot. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Ein Tab‑Separated Values (TSV)‑Dateiformat stellt Daten dar, die in Klartext durch Tabulatoren getrennt sind. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM ist eine Makro‑aktivierte Add‑In‑Datei, die verwendet wird, um neue Funktionen zu Tabellenkalkulationen hinzuzufügen. Ein Add‑In ist ein ergänzendes Programm, das zusätzlichen Code ausführt und zusätzliche Funktionalität für Tabellenkalkulationen bereitstellt. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS steht für das Excel Binary File Format. Solche Dateien können von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Das XLSB‑Dateiformat definiert das Excel Binary File Format, das eine Sammlung von Datensätzen und Strukturen ist, die den Inhalt einer Excel‑Arbeitsmappe festlegen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM ist ein Typ von Tabellenkalkulationsdateien, die Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX ist ein bekanntes Format für Microsoft‑Excel‑Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Dateien mit der .XLT-Erweiterung sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft‑Office‑Suite ist. Microsoft Office 97‑2003 unterstützte das Erstellen neuer XLT‑Dateien sowie das Öffnen dieser. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | Die XLTM-Dateierweiterung steht für Dateien, die von Microsoft Excel als makro‑aktivierte Vorlagendateien erzeugt werden. XLTM‑Dateien sind in ihrer Struktur XLTX‑Dateien ähnlich, abgesehen davon, dass letztere keine Vorlagendateien mit Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | Die XLTX-Datei stellt eine Microsoft Excel-Vorlage dar, die auf den Office OpenXML-Dateiformatspezifikationen basiert. Sie wird verwendet, um eine Standardvorlagendatei zu erstellen, die zur Erzeugung von XLSX-Dateien genutzt werden kann, die dieselben Einstellungen wie in der XLTX-Datei angegeben aufweisen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xltx). |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
