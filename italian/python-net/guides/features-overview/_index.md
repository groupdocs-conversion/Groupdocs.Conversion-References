---
title: "Panoramica delle funzionalità"
linkTitle: "Features overview"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Caratteristiche principali di GroupDocs.Conversion per Python via .NET — oltre 10.000 coppie di formati, selezione di pagine, opzioni di caricamento/conversione, filigrane, ispezione dei documenti e integrazione della pipeline AI."
type: docs
url: /it/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion per Python via .NET converte documenti tra **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, immagini, CAD, email, archivi, eBook, HTML, TeX e linguaggi di descrizione delle pagine. Funziona interamente on-premise, non richiede l'installazione di Microsoft Office o Adobe Acrobat, e viene distribuito come wheel precompilato su Windows, Linux e macOS.

Vedi l'elenco completo dei [formati supportati]() o sfoglia la [Guida per sviluppatori]() per esempi eseguibili di ogni superficie API.

## File Conversion

La capacità principale è convertire qualsiasi documento sorgente supportato in qualsiasi formato di destinazione supportato. Tutte le conversioni sono possibili senza l'installazione di Microsoft Office, LibreOffice o Adobe Acrobat. GroupDocs.Conversion offre un set flessibile di opzioni per personalizzare la pipeline.

### Convert specific document pages

Converti documenti interi, pagine individuali o intervalli di pagine. Usa una lista esplicita di `pages` o un intervallo `page_number` + `pages_count` sulla classe [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Vedi [Convert a Document to Another Format]() per esempi eseguibili.

### Per-page file output

Genera un file di output per pagina — utile per presentazioni, PDF multi-pagina e rendering di documenti in immagini. Itera l'attributo `page_number` mantenendo `pages_count = 1`. Vedi [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

Quando un file sorgente arriva come flusso di byte senza nome file, GroupDocs.Conversion rileva automaticamente il formato ispezionando l'intestazione del flusso. Vedi [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Ogni classe di opzioni di caricamento espone impostazioni specifiche del formato:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Interroga il motore per i formati di destinazione supportati prima di eseguire una pipeline — a livello di intera libreria, per estensione o per un documento caricato specifico. Vedi [Get Possible Conversions]() per i tre overload.

### Watermark the converted document

Aggiungi una filigrana di testo durante la conversione — controlla colore, dimensione, rotazione, trasparenza e posizionamento sfondo / primo piano. Vedi [Add a Watermark to Converted Document]().

### Convert files inside a container

Apri contenitori ZIP, RAR, 7Z, OST o PST, converti i contenuti e scrivi un documento di output consolidato in una singola chiamata. Vedi [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion può leggere i metadati da un documento sorgente senza effettivamente convertirlo — formato, numero di pagine o di diapositive, autore, data di creazione, dimensioni, indice e dettagli specifici del formato. Vedi [Getting Document Information]() per tutte le nove varianti:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Il costruttore Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) accetta sia un percorso file che un oggetto binario simile a un file, così puoi caricare documenti da:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

L'archiviazione cloud (Amazon S3, Azure Blob Storage, Google Cloud Storage) funziona recuperando i byte in un buffer `BytesIO` e passandolo al costruttore di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

## Logging and Diagnostics

Collega un [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) tramite [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) per tracciare la pipeline di conversione — selezione del loader, avvio e completamento della conversione, e eventuali avvisi generati dal motore. Vedi [Registrazione e diagnostica]().

## AI and LLM Integration

GroupDocs.Conversion è progettato per essere un componente di prima classe per le pipeline di documenti AI. Il pacchetto pip `groupdocs-conversion-net` include un file `AGENTS.md` all'interno del wheel in modo che gli assistenti di codifica AI possano scoprire automaticamente l'API, e GroupDocs gestisce un [server MCP](https://docs.groupdocs.com/mcp) pubblico per ricerche di documentazione su richiesta. Vedi [Integrazione di Agent e LLM]().

## On-Premise Deployment

Nessuna chiamata al cloud, nessun traffico di rete in uscita, nessuna dipendenza software di terze parti oltre a quelle fornite dal sistema operativo. Il wheel è autonomo su Windows e include le proprie librerie runtime native su Linux e macOS. Vedi [Requisiti di sistema]().
