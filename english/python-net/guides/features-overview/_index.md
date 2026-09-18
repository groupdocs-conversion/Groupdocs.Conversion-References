---
title: Features Overview
linkTitle: "Features overview"
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Key features of GroupDocs.Conversion for Python via .NET — 10,000+ format pairs, page selection, load/convert options, watermarks, document inspection, and AI-pipeline integration."
type: docs
url: /python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion for Python via .NET converts documents between **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, images, CAD, email, archives, eBooks, HTML, TeX, and page-description languages. It runs entirely on-premise, requires no Microsoft Office or Adobe Acrobat installation, and ships as a pre-built wheel on Windows, Linux, and macOS.

See the full list of [supported formats]() or browse the [Developer Guide]() for runnable examples of every API surface.

## File Conversion

The core capability is converting any supported source document into any supported target format. All conversions are possible without Microsoft Office, LibreOffice, or Adobe Acrobat installed. GroupDocs.Conversion offers a flexible set of options to customise the pipeline.

### Convert specific document pages

Convert whole documents, individual pages, or page ranges. Use either an explicit `pages` list or a `page_number` + `pages_count` range on the [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) class. See [Convert a Document to Another Format]() for runnable examples.

### Per-page file output

Emit one output file per page — useful for presentations, multi-page PDFs, and rendering documents to images. Loop the `page_number` attribute while keeping `pages_count = 1`. See [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

When a source file arrives as a byte stream with no file name, GroupDocs.Conversion detects the format automatically by inspecting the stream header. See [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Every load options class exposes format-specific settings:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Query the engine for supported target formats before running a pipeline — at the whole-library level, by extension, or for a specific loaded document. See [Get Possible Conversions]() for the three overloads.

### Watermark the converted document

Add a text watermark while converting — control colour, size, rotation, transparency, and background / foreground placement. See [Add a Watermark to Converted Document]().

### Convert files inside a container

Open ZIP, RAR, 7Z, OST, or PST containers, convert the contents, and write a consolidated output document in a single call. See [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion can read metadata from a source document without actually converting it — format, page or slide count, author, creation date, dimensions, table of contents, and format-specific details. See [Getting Document Information]() for all nine variants:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

The Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) constructor accepts both a file path and a binary file-like object, so you can load documents from:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

Cloud storage (Amazon S3, Azure Blob Storage, Google Cloud Storage) works by fetching bytes into a `BytesIO` buffer and passing it to the [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) constructor.

## Logging and Diagnostics

Wire a [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) through [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) to trace the conversion pipeline — loader selection, conversion start and completion, and any warnings raised by the engine. See [Logging and Diagnostics]().

## AI and LLM Integration

GroupDocs.Conversion is designed to be a first-class building block for AI document pipelines. The `groupdocs-conversion-net` pip package ships an `AGENTS.md` file inside the wheel so AI coding assistants can discover the API surface automatically, and GroupDocs runs a public [MCP server](https://docs.groupdocs.com/mcp) for on-demand documentation lookups. See [Agents and LLM Integration]() for the full story — including how to chain GroupDocs.Conversion with GroupDocs.Markdown for clean RAG input.

## On-Premise Deployment

No cloud calls, no outbound network traffic, no third-party software dependencies beyond what the OS already provides. The wheel is self-contained on Windows and ships its own native runtime libraries on Linux and macOS. See [System Requirements]() for the short list of optional native packages (`libgdiplus`, ICU, fontconfig).
