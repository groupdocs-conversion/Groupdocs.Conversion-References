---
title: "Översikt över funktioner"
linkTitle: "Features overview"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Viktiga funktioner i GroupDocs.Conversion för Python via .NET — 10 000+ formatpar, sidval, laddnings-/konverteringsalternativ, vattenstämplar, dokumentinspektion och AI‑pipeline‑integration."
type: docs
url: /sv/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion för Python via .NET konverterar dokument mellan **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, bilder, CAD, e‑post, arkiv, e‑böcker, HTML, TeX och sidbeskrivningsspråk. Det körs helt på plats, kräver ingen installation av Microsoft Office eller Adobe Acrobat, och levereras som ett förbyggt wheel på Windows, Linux och macOS.

Se den fullständiga listan över [stödda format]() eller bläddra i [Utvecklarguide]() för körbara exempel på hela API‑ytan.

## File Conversion

Den grundläggande funktionen är att konvertera vilket som helst stödjt källdokument till vilket som helst stödjt målformat. Alla konverteringar är möjliga utan att Microsoft Office, LibreOffice eller Adobe Acrobat är installerade. GroupDocs.Conversion erbjuder en flexibel uppsättning alternativ för att anpassa pipelinen.

### Convert specific document pages

Konvertera hela dokument, enskilda sidor eller sidintervall. Använd antingen en explicit `pages`‑lista eller ett `page_number` + `pages_count`‑intervall på klassen [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Se [Convert a Document to Another Format]() för körbara exempel.

### Per-page file output

Skapa en utdatafil per sida — användbart för presentationer, flersidiga PDF‑filer och rendering av dokument till bilder. Loopa `page_number`‑attributet medan `pages_count = 1`. Se [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

När en källfil anländer som en byte‑ström utan filnamn upptäcker GroupDocs.Conversion formatet automatiskt genom att inspektera strömhuvudet. Se [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Varje klass för laddningsalternativ exponerar format‑specifika inställningar:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Fråga motorn om vilka målformat som stöds innan en pipeline körs — på hela bibliotekets nivå, per filändelse eller för ett specifikt laddat dokument. Se [Get Possible Conversions]() för de tre överlagringarna.

### Watermark the converted document

Lägg till en textvattenstämpel vid konvertering — kontrollera färg, storlek, rotation, transparens samt placering i bakgrund/förgrund. Se [Add a Watermark to Converted Document]().

### Convert files inside a container

Öppna ZIP-, RAR-, 7Z-, OST- eller PST‑behållare, konvertera innehållet och skriv ett konsoliderat utdokument i ett enda anrop. Se [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion kan läsa metadata från ett källdokument utan att faktiskt konvertera det — format, sid- eller bildantal, författare, skapelsedatum, dimensioner, innehållsförteckning och format‑specifika detaljer. Se [Getting Document Information]() för alla nio varianter:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑konstruktorn accepterar både en filsökväg och ett binärt fil‑liknande objekt, så att du kan läsa in dokument från:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

Molnlagring (Amazon S3, Azure Blob Storage, Google Cloud Storage) fungerar genom att hämta byte till en `BytesIO`‑buffer och skicka den till [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑konstruktorn.

## Logging and Diagnostics

Koppla en [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) via [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) för att spåra konverterings‑pipeline — val av laddare, start och slutförande av konvertering samt eventuella varningar som motorn ger. Se [Logging and Diagnostics]().

## AI and LLM Integration

GroupDocs.Conversion är utformad för att vara en förstklassig byggsten i AI‑dokument‑pipelines. `groupdocs-conversion-net`‑pip‑paketet levererar en `AGENTS.md`‑fil i hjulet så att AI‑kodassistenter automatiskt kan upptäcka API‑ytan, och GroupDocs driver en offentlig [MCP server](https://docs.groupdocs.com/mcp) för dokumentationsuppslag på begäran. Se [Agents and LLM Integration]() för hela historien — inklusive hur man kedjar GroupDocs.Conversion med GroupDocs.Markdown för ren RAG‑inmatning.

## On-Premise Deployment

Inga molnanrop, ingen utgående nätverkstrafik, inga tredjepartsprogramvaruberoenden utöver vad OS redan tillhandahåller. Hjulet är självständigt på Windows och levererar sina egna inhemska runtime‑bibliotek på Linux och macOS. Se [System Requirements]() för den korta listan över valfria inhemska paket (ICU, fontconfig, Microsoft core fonts).
