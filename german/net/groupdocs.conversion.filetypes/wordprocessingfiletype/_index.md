---
title: WordProcessingFileType
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Definiert Textverarbeitungsdateien die Benutzerinformationen im NurText oder RichTextFormat enthalten. Ein NurTextDateiformat enthält unformatierten Text und es können keine Schriftart oder Seiteneinstellungen usw. angewendet werden. Im Gegensatz dazu ermöglicht ein RichTextDateiformat Formatierungsoptionen wie das Festlegen von Schriftarten Stilen fett kursiv unterstrichen usw. Seitenränder Überschriften Aufzählungszeichen und Zahlen sowie mehrere andere Formatierungsfunktionen. Enthält die folgenden Dateitypen Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi./wordprocessingfiletype/mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log./wordprocessingfiletype/log . Erfahren Sie mehr über Textverarbeitungsformatehierhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 960
url: /de/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Definiert Textverarbeitungsdateien, die Benutzerinformationen im Nur-Text- oder Rich-Text-Format enthalten. Ein Nur-Text-Dateiformat enthält unformatierten Text und es können keine Schriftart- oder Seiteneinstellungen usw. angewendet werden. Im Gegensatz dazu ermöglicht ein Rich-Text-Dateiformat Formatierungsoptionen wie das Festlegen von Schriftarten, Stilen (fett, kursiv, unterstrichen usw.), Seitenränder, Überschriften, Aufzählungszeichen und Zahlen sowie mehrere andere Formatierungsfunktionen. Enthält die folgenden Dateitypen: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`Mobi`](./mobi) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . [`Log`](./log) . Erfahren Sie mehr über Textverarbeitungsformate[hier](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Azw3](../../groupdocs.conversion.filetypes/wordprocessingfiletype/azw3) | AZW3, auch bekannt als Kindle Format 8 (KF8), ist die modifizierte Version des digitalen Dateiformats AZW eBook, das für Amazon Kindle-Geräte entwickelt wurde. Das Format ist eine Erweiterung älterer AZW-Dateien und wird auf Kindle Fire-Geräten nur mit Abwärtskompatibilität für das Vorgängerdateiformat, dh MOBI und AZW, verwendet. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Dateien mit der Erweiterung .doc stellen Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsdokumenten im binären Dateiformat erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM-Dateien sind Microsoft Word 2007 oder höher erstellte Dokumente mit der Fähigkeit, Makros auszuführen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX ist ein bekanntes Format für Microsoft Word-Dokumente. Die Struktur dieses neuen Dokumentformats, das 2007 mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde, wurde von einer reinen Binärdatei in eine Kombination aus XML- und Binärdateien geändert. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Dateien mit der Erweiterung .DOT sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Generierung weiterer DOC- oder DOCX-Dateien zu haben. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Eine Datei mit DOTM-Erweiterung stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Dateien mit der Erweiterung DOTX sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Generierung weiterer DOCX-Dateien zu haben. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Log](../../groupdocs.conversion.filetypes/wordprocessingfiletype/log) | Eine Datei mit der Erweiterung .LOG stellt ein Textdokument dar, das einfachen Text in Form von Zeilen enthält. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Textdateien, die mit Dialekten der Markdown-Sprache erstellt wurden, werden mit der Dateierweiterung .MD oder .MARKDOWN gespeichert. MD-Dateien werden im Klartextformat gespeichert, das die Markdown-Sprache verwendet, die auch Inline-Textsymbole enthält, die definieren, wie ein Text formatiert werden kann, z. B. Einrückungen, Tabellenformatierung, Schriftarten und Kopfzeilen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/wordprocessingfiletype/mobi) | Das MOBI-Dateiformat ist eines der am weitesten verbreiteten E-Book-Dateiformate. Das Format ist eine Erweiterung des alten OEB-Formats (Open Ebook Format) und wurde als proprietäres Format für Mobipocket Reader verwendet. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/ebook/mobi) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT-Dateien sind Dokumenttypen, die mit Textverarbeitungsanwendungen erstellt wurden, die auf dem OpenDocument-Textdateiformat basieren. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Dateien mit der Erweiterung OTT stellen Vorlagendokumente dar, die von Anwendungen in Übereinstimmung mit dem OpenDocument-Standardformat von OASIS generiert wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Das von Microsoft eingeführte und dokumentierte Rich Text Format (RTF) stellt eine Methode zum Codieren von formatiertem Text und Grafiken zur Verwendung in Anwendungen dar. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Sql](../../groupdocs.conversion.filetypes/wordprocessingfiletype/sql) | Eine Datei mit der Erweiterung .SQL stellt ein Textdokument dar, das SQL enthält. |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Eine Datei mit der Erweiterung .TXT stellt ein Textdokument dar, das einfachen Text in Form von Zeilen enthält. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/txt) . |

### Siehe auch

* class [FileType](../filetype)
* namensraum [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
