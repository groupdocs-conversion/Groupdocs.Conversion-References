---
title: "Обзор функций"
linkTitle: "Features overview"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Ключевые возможности GroupDocs.Conversion для Python через .NET — более 10 000 пар форматов, выбор страниц, параметры загрузки/конвертации, водяные знаки, проверка документов и интеграция AI‑конвейера."
type: docs
url: /ru/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion для Python через .NET преобразует документы между **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, изображения, CAD, электронная почта, архивы, электронные книги, HTML, TeX и языки описания страниц. Он полностью работает в локальной среде, не требует установки Microsoft Office или Adobe Acrobat и распространяется в виде готового wheel для Windows, Linux и macOS.

Смотрите полный список [список поддерживаемых форматов]() или просмотрите [Руководство разработчика]() для работающих примеров всех возможностей API.

## File Conversion

Основная возможность — конвертация любого поддерживаемого исходного документа в любой поддерживаемый целевой формат. Все преобразования возможны без установленного Microsoft Office, LibreOffice или Adobe Acrobat. GroupDocs.Conversion предлагает гибкий набор параметров для настройки конвейера.

### Convert specific document pages

Конвертируйте целые документы, отдельные страницы или диапазоны страниц. Используйте либо явный список `pages`, либо диапазон `page_number` + `pages_count` в классе [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Смотрите [Convert a Document to Another Format]() для работающих примеров.

### Per-page file output

Создавайте один выходной файл на страницу — удобно для презентаций, многостраничных PDF и рендеринга документов в изображения. Перебирайте атрибут `page_number`, удерживая `pages_count = 1`. Смотрите [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

Когда исходный файл поступает в виде байтового потока без имени файла, GroupDocs.Conversion автоматически определяет формат, анализируя заголовок потока. Смотрите [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Каждый класс параметров загрузки раскрывает настройки, специфичные для формата:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Запросите у движка поддерживаемые целевые форматы перед запуском конвейера — на уровне всей библиотеки, по расширению или для конкретного загруженного документа. Смотрите [Get Possible Conversions]() для трёх перегрузок.

### Watermark the converted document

Добавьте текстовый водяной знак при конвертации — управляйте цветом, размером, вращением, прозрачностью и размещением в фоне/переднем плане. Смотрите [Add a Watermark to Converted Document]().

### Convert files inside a container

Откройте контейнеры ZIP, RAR, 7Z, OST или PST, конвертируйте их содержимое и запишите объединённый выходной документ одним вызовом. Смотрите [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion может считывать метаданные из исходного документа без его фактической конвертации — формат, количество страниц или слайдов, автор, дата создания, размеры, оглавление и детали, специфичные для формата. Смотрите [Getting Document Information]() для всех девяти вариантов:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Конструктор Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) принимает как путь к файлу, так и бинарный объект, похожий на файл, поэтому вы можете загружать документы из:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

Облачное хранилище (Amazon S3, Azure Blob Storage, Google Cloud Storage) работает, получая байты в буфер `BytesIO` и передавая их конструктору [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

## Logging and Diagnostics

Подключите [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) через [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) для отслеживания конвейера конвертации — выбор загрузчика, начало и завершение конвертации, а также любые предупреждения, выдаваемые движком. См. [Журналирование и диагностика]().

## AI and LLM Integration

GroupDocs.Conversion разработан как первоклассный строительный блок для AI‑конвейеров обработки документов. Пакет `groupdocs-conversion-net` для pip поставляется с файлом `AGENTS.md` внутри колеса, чтобы AI‑помощники по кодированию могли автоматически обнаруживать поверхность API, а GroupDocs запускает публичный [MCP server](https://docs.groupdocs.com/mcp) для запросов документации по требованию. См. [Интеграция агентов и LLM]().

## On-Premise Deployment

Нет облачных вызовов, нет исходящего сетевого трафика, нет сторонних программных зависимостей, кроме тех, что уже предоставляет ОС. Колесо полностью автономно в Windows и поставляется со своими собственными нативными библиотеками времени выполнения в Linux и macOS. См. [Системные требования]().
