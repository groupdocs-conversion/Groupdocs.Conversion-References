---
title: "Overzicht van functies"
linkTitle: "Features overview"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Belangrijkste functies van GroupDocs.Conversion voor Python via .NET — meer dan 10.000 formaatparen, paginaselectie, laad-/conversie‑opties, watermerken, documentinspectie en AI‑pipeline‑integratie."
type: docs
url: /nl/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion voor Python via .NET converteert documenten tussen **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, afbeeldingen, CAD, e‑mail, archieven, eBooks, HTML, TeX en paginabeschrijvings‑talen. Het draait volledig on‑premise, vereist geen installatie van Microsoft Office of Adobe Acrobat, en wordt geleverd als een vooraf gebouwde wheel voor Windows, Linux en macOS.

Bekijk de volledige lijst van [ondersteunde formaten]() of blader door de [Ontwikkelaarsgids]() voor uitvoerbare voorbeelden van elke API‑laag.

## File Conversion

De kernfunctionaliteit is het converteren van elk ondersteund brondocument naar elk ondersteund doelformaat. Alle conversies zijn mogelijk zonder dat Microsoft Office, LibreOffice of Adobe Acrobat geïnstalleerd zijn. GroupDocs.Conversion biedt een flexibele reeks opties om de pipeline aan te passen.

### Convert specific document pages

Converteer volledige documenten, individuele pagina's of paginabereiken. Gebruik ofwel een expliciete `pages`‑lijst of een `page_number` + `pages_count`‑bereik op de [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/)‑klasse. Zie [Convert a Document to Another Format]() voor uitvoerbare voorbeelden.

### Per-page file output

Genereer één uitvoerbestand per pagina — handig voor presentaties, meerpagina‑PDF’s en het renderen van documenten naar afbeeldingen. Loop over het `page_number`‑attribuut terwijl `pages_count = 1` blijft. Zie [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

Wanneer een bronbestand arriveert als een byte‑stream zonder bestandsnaam, detecteert GroupDocs.Conversion het formaat automatisch door de stream‑header te inspecteren. Zie [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Elke laad‑opties‑klasse biedt formaat‑specifieke instellingen:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Vraag de engine naar ondersteunde doelformaten voordat je een pipeline uitvoert — op bibliotheek‑niveau, per extensie, of voor een specifiek geladen document. Zie [Get Possible Conversions]() voor de drie overloads.

### Watermark the converted document

Voeg een tekst‑watermerk toe tijdens het converteren — beheer kleur, grootte, rotatie, transparantie en plaatsing van achtergrond/voorgrond. Zie [Add a Watermark to Converted Document]().

### Convert files inside a container

Open ZIP-, RAR-, 7Z-, OST- of PST‑containers, converteer de inhoud en schrijf een geconsolideerd uitvoerdocument in één enkele oproep. Zie [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion kan metadata lezen uit een brondocument zonder het daadwerkelijk te converteren — formaat, pagina‑ of slide‑aantal, auteur, aanmaakdatum, afmetingen, inhoudsopgave en formaat‑specifieke details. Zie [Getting Document Information]() voor alle negen varianten:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

De Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑constructor accepteert zowel een bestandspad als een binair bestand‑achtig object, zodat je documenten kunt laden van:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

Cloudopslag (Amazon S3, Azure Blob Storage, Google Cloud Storage) werkt door bytes op te halen in een `BytesIO` buffer en deze door te geven aan de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) constructor.

## Logging and Diagnostics

Verbind een [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) via [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) om de conversiepijplijn te volgen — selectie van de loader, start en voltooiing van de conversie, en eventuele waarschuwingen die door de engine worden gegenereerd. Zie [Logging en diagnostiek]().

## AI and LLM Integration

GroupDocs.Conversion is ontworpen als een eersteklas bouwsteen voor AI‑documentpijplijnen. Het `groupdocs-conversion-net` pip‑pakket levert een `AGENTS.md`‑bestand in de wheel zodat AI‑code‑assistenten automatisch de API‑oppervlakte kunnen ontdekken, en GroupDocs draait een openbare [MCP server](https://docs.groupdocs.com/mcp) voor documentatie‑opvragingen op aanvraag. Zie [Agents en LLM‑integratie](). voor het volledige verhaal — inclusief hoe je GroupDocs.Conversion kunt koppelen aan GroupDocs.Markdown voor schone RAG‑invoer.

## On-Premise Deployment

Geen cloud‑aanroepen, geen uitgaand netwerkverkeer, geen afhankelijkheden van derden buiten wat het OS al biedt. De wheel is zelfvoorzienend op Windows en levert zijn eigen native runtime‑bibliotheken op Linux en macOS. Zie [Systeemvereisten](). voor de korte lijst van optionele native pakketten (ICU, fontconfig, Microsoft core fonts).
