---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert Textverarbeitungsdateien, die Benutzerinformationen im Nur‑Text‑ oder Rich‑Text‑Format enthalten. Ein Nur‑Text‑Dateiformat enthält unformatierten Text, auf den keine Schrift‑ oder Seiteneinstellungen usw. angewendet werden können. Im Gegensatz dazu ermöglicht ein Rich‑Text‑Dateiformat Formatierungsoptionen wie das Festlegen von Schriftarten, Typen, Stilen, fett, kursiv, Unterstreichungen usw., Seitenränder, Überschriften, Aufzählungen und Nummerierungen sowie mehrere andere Formatierungsfunktionen. Enthält die folgenden Dateitypen Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. Erfahren Sie mehr über Textverarbeitungsformate hierhttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /de/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Definiert Textverarbeitungsdateien, die Benutzerinformationen im Klartext- oder Rich‑Text-Format enthalten. Ein Klartext‑Dateiformat enthält unformatierten Text und es können keine Schrift‑ oder Seiteneinstellungen usw. angewendet werden. Im Gegensatz dazu ermöglicht ein Rich‑Text‑Dateiformat Formatierungsoptionen wie das Festlegen von Schriftarten, Stilen (fett, kursiv, unterstrichen usw.), Seitenrändern, Überschriften, Aufzählungen und Nummerierungen sowie mehrere andere Formatierungsfunktionen. Enthält die folgenden Dateitypen: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Erfahren Sie mehr über Textverarbeitungsformate [hier](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Dateien mit der Erweiterung .doc stellen Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärdateiformat erzeugt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM‑Dateien sind von Microsoft Word 2007 oder höher erzeugte Dokumente mit der Möglichkeit, Makros auszuführen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Eingeführt ab 2007 mit der Veröffentlichung von Microsoft Office 2007, wurde die Struktur dieses neuen Dokumentformats von reinem Binärformat zu einer Kombination aus XML‑ und Binärdateien geändert. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Dateien mit der Erweiterung .DOT sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOC‑ oder DOCX‑Dateien zu besitzen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Eine Datei mit der Erweiterung DOTM stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Dateien mit der Erweiterung DOTX sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOCX‑Dateien zu besitzen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word ist Office Open XML WordprocessingML, das in einer flachen XML‑Datei anstelle eines ZIP‑Pakets gespeichert wird. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Textdateien, die mit Markdown‑Sprachdialekten erstellt wurden, werden mit der Dateierweiterung .MD oder .MARKDOWN gespeichert. MD‑Dateien werden im Klartextformat gespeichert, das die Markdown‑Sprache verwendet, die auch Inline‑Textsymbole enthält und definiert, wie ein Text formatiert werden kann, z. B. Einrückungen, Tabellenformatierung, Schriftarten und Überschriften. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT‑Dateien sind Dokumente, die mit Textverarbeitungsanwendungen erstellt werden und auf dem OpenDocument‑Textdateiformat basieren. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Dateien mit der OTT-Erweiterung stellen Vorlagendokumente dar, die von Anwendungen gemäß dem OASIS OpenDocument-Standardformat erzeugt werden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Von Microsoft eingeführt und dokumentiert, stellt das Rich Text Format (RTF) eine Methode zur Kodierung von formatiertem Text und Grafiken für die Verwendung in Anwendungen dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Eine Datei mit der .TXT-Erweiterung stellt ein Textdokument dar, das reinen Text in Form von Zeilen enthält. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/txt). |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
