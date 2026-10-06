---
title: "Resumen de características"
linkTitle: "Features overview"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Características clave de GroupDocs.Conversion para Python vía .NET — más de 10 000 pares de formatos, selección de páginas, opciones de carga/conversión, marcas de agua, inspección de documentos e integración de canal de IA."
type: docs
url: /es/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion para Python vía .NET convierte documentos entre **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, imágenes, CAD, correo electrónico, archivos comprimidos, eBooks, HTML, TeX y lenguajes de descripción de página. Se ejecuta completamente en local, no requiere instalación de Microsoft Office ni Adobe Acrobat, y se distribuye como una rueda preconstruida en Windows, Linux y macOS.

Consulte la lista completa de [formatos compatibles]() o explore la [Guía del desarrollador]() para ejemplos ejecutables de toda la superficie de la API.

## File Conversion

La capacidad principal es convertir cualquier documento fuente compatible en cualquier formato de destino compatible. Todas las conversiones son posibles sin que Microsoft Office, LibreOffice o Adobe Acrobat estén instalados. GroupDocs.Conversion ofrece un conjunto flexible de opciones para personalizar el flujo de trabajo.

### Convert specific document pages

Convierta documentos completos, páginas individuales o rangos de páginas. Utilice una lista explícita de `pages` o un rango `page_number` + `pages_count` en la clase [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Consulte [Convert a Document to Another Format]() para ejemplos ejecutables.

### Per-page file output

Genere un archivo de salida por página — útil para presentaciones, PDFs multipágina y renderizado de documentos a imágenes. Itere el atributo `page_number` manteniendo `pages_count = 1`. Consulte [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

Cuando un archivo fuente llega como un flujo de bytes sin nombre de archivo, GroupDocs.Conversion detecta el formato automáticamente inspeccionando el encabezado del flujo. Consulte [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Cada clase de opciones de carga expone configuraciones específicas del formato:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Consulte al motor los formatos de destino compatibles antes de ejecutar un flujo de trabajo — a nivel de toda la biblioteca, por extensión o para un documento cargado específico. Consulte [Get Possible Conversions]() para las tres sobrecargas.

### Watermark the converted document

Añada una marca de agua de texto durante la conversión — controle el color, tamaño, rotación, transparencia y la ubicación de fondo/primer plano. Consulte [Add a Watermark to Converted Document]().

### Convert files inside a container

Abra contenedores ZIP, RAR, 7Z, OST o PST, convierta su contenido y genere un documento de salida consolidado en una única llamada. Consulte [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion puede leer metadatos de un documento fuente sin convertirlo realmente — formato, número de páginas o diapositivas, autor, fecha de creación, dimensiones, tabla de contenidos y detalles específicos del formato. Consulte [Getting Document Information]() para las nueve variantes:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

El constructor Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) acepta tanto una ruta de archivo como un objeto binario similar a un archivo, por lo que puede cargar documentos desde:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

El almacenamiento en la nube (Amazon S3, Azure Blob Storage, Google Cloud Storage) funciona obteniendo bytes en un búfer `BytesIO` y pasándolo al constructor de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

## Logging and Diagnostics

Conecta un [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) mediante [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) para rastrear la canalización de conversión — selección del cargador, inicio y finalización de la conversión, y cualquier advertencia generada por el motor. Consulta [Registro y diagnóstico]().

## AI and LLM Integration

GroupDocs.Conversion está diseñado para ser un bloque de construcción de primera clase para canalizaciones de documentos de IA. El paquete pip `groupdocs-conversion-net` incluye un archivo `AGENTS.md` dentro del wheel para que los asistentes de codificación de IA puedan descubrir la superficie de la API automáticamente, y GroupDocs ejecuta un [servidor MCP](https://docs.groupdocs.com/mcp) público para consultas de documentación bajo demanda. Consulta [Integración de agentes y LLM]()` para la historia completa — incluyendo cómo encadenar GroupDocs.Conversion con GroupDocs.Markdown para una entrada RAG limpia.

## On-Premise Deployment

Sin llamadas a la nube, sin tráfico de red saliente, sin dependencias de software de terceros más allá de lo que el SO ya proporciona. El wheel es autónomo en Windows y lleva sus propias bibliotecas nativas en Linux y macOS. Consulta [Requisitos del sistema]() para la lista breve de paquetes nativos opcionales (ICU, fontconfig, fuentes centrales de Microsoft).
