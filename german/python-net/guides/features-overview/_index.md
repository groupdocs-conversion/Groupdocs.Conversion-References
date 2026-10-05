---
title: "Übersicht der Funktionen"
linkTitle: "Features overview"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Wichtige Funktionen von GroupDocs.Conversion für Python via .NET — über 10.000 Formatpaare, Seitenauswahl, Lade‑/Konvertierungsoptionen, Wasserzeichen, Dokumenteninspektion und AI‑Pipeline‑Integration."
type: docs
url: /de/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion für Python via .NET konvertiert Dokumente zwischen **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, Bilder, CAD, E‑Mail, Archive, eBooks, HTML, TeX und Seitenbeschreibungssprachen. Es läuft vollständig on‑premise, erfordert keine Installation von Microsoft Office oder Adobe Acrobat und wird als vorgefertigtes Wheel für Windows, Linux und macOS bereitgestellt.

Siehe die vollständige Liste der [unterstützten Formate]() oder durchsuchen Sie den [Entwicklerleitfaden]() für ausführbare Beispiele jeder API‑Oberfläche.

## File Conversion

Die Kernfunktion besteht darin, jedes unterstützte Quelldokument in jedes unterstützte Zielformat zu konvertieren. Alle Konvertierungen sind ohne installierte Microsoft Office, LibreOffice oder Adobe Acrobat möglich. GroupDocs.Conversion bietet einen flexiblen Satz von Optionen zur Anpassung der Pipeline.

### Convert specific document pages

Konvertieren Sie ganze Dokumente, einzelne Seiten oder Seitenbereiche. Verwenden Sie entweder eine explizite `pages`‑Liste oder einen `page_number` + `pages_count`‑Bereich in der Klasse [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Siehe [Convert a Document to Another Format]() für ausführbare Beispiele.

### Per-page file output

Erzeugen Sie eine Ausgabedatei pro Seite — nützlich für Präsentationen, mehrseitige PDFs und das Rendern von Dokumenten zu Bildern. Durchlaufen Sie das Attribut `page_number`, während `pages_count = 1` bleibt. Siehe [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

Wenn eine Quelldatei als Bytestrom ohne Dateinamen ankommt, erkennt GroupDocs.Conversion das Format automatisch, indem es den Stream‑Header inspiziert. Siehe [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Jede Ladeoptionen‑Klasse stellt format‑spezifische Einstellungen bereit:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Fragen Sie die Engine nach unterstützten Zielformaten, bevor Sie eine Pipeline ausführen — auf Bibliotheksebene, nach Erweiterung oder für ein bestimmtes geladenes Dokument. Siehe [Get Possible Conversions]() für die drei Überladungen.

### Watermark the converted document

Fügen Sie beim Konvertieren ein Textwasserzeichen hinzu — steuern Sie Farbe, Größe, Drehung, Transparenz und die Platzierung im Hintergrund / Vordergrund. Siehe [Add a Watermark to Converted Document]().

### Convert files inside a container

Öffnen Sie ZIP-, RAR-, 7Z-, OST- oder PST-Container, konvertieren Sie den Inhalt und schreiben Sie ein konsolidiertes Ausgabedokument in einem einzigen Aufruf. Siehe [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion kann Metadaten aus einem Quelldokument lesen, ohne es tatsächlich zu konvertieren — Format, Seiten‑ oder Folienanzahl, Autor, Erstellungsdatum, Abmessungen, Inhaltsverzeichnis und format‑spezifische Details. Siehe [Getting Document Information]() für alle neun Varianten:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Der Python‑[`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑Konstruktor akzeptiert sowohl einen Dateipfad als auch ein binäres dateiähnliches Objekt, sodass Sie Dokumente laden können von:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

Cloud‑Speicher (Amazon S3, Azure Blob Storage, Google Cloud Storage) funktioniert, indem Bytes in einen `BytesIO`‑Puffer geladen und an den [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑Konstruktor übergeben werden.

## Logging and Diagnostics

Verbinden Sie einen [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) über [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/), um die Konvertierungspipeline zu verfolgen — Auswahl des Laders, Start und Abschluss der Konvertierung sowie alle vom Engine erzeugten Warnungen. Siehe [Logging and Diagnostics]().

## AI and LLM Integration

GroupDocs.Conversion ist als erstklassiger Baustein für KI‑Dokument‑Pipelines konzipiert. Das `groupdocs-conversion-net`‑pip‑Paket liefert eine `AGENTS.md`‑Datei im Wheel, damit KI‑Code‑Assistenten die API‑Oberfläche automatisch entdecken können, und GroupDocs betreibt einen öffentlichen [MCP server](https://docs.groupdocs.com/mcp) für Abrufe von Dokumentation auf Abruf. Siehe [Agents and LLM Integration]() für die vollständige Geschichte — einschließlich wie man GroupDocs.Conversion mit GroupDocs.Markdown für saubere RAG‑Eingaben verknüpft.

## On-Premise Deployment

Keine Cloud‑Aufrufe, kein ausgehender Netzwerkverkehr, keine Drittanbieter‑Softwareabhängigkeiten über das hinaus, was das Betriebssystem bereits bereitstellt. Das Wheel ist unter Windows eigenständig und liefert eigene native Laufzeitbibliotheken unter Linux und macOS. Siehe [System Requirements]() für die kurze Liste optionaler nativer Pakete (ICU, fontconfig, Microsoft‑Core‑Fonts).
