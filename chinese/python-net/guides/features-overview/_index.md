---
title: "功能概览"
linkTitle: "Features overview"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "GroupDocs.Conversion for Python via .NET 的关键特性 — 超过 10,000 种格式对、页面选择、加载/转换选项、水印、文档检查以及 AI 流水线集成。"
type: docs
url: /zh/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion for Python via .NET 在 **10,000+ format pairs** 之间转换文档 — Microsoft Office、PDF、OpenDocument、图像、CAD、电子邮件、压缩文件、电子书、HTML、TeX 以及页面描述语言。它完全在本地运行，无需安装 Microsoft Office 或 Adobe Acrobat，并以预构建的 wheel 形式在 Windows、Linux 和 macOS 上提供。

查看完整的 [supported formats]() 列表，或浏览 [Developer Guide]() 以获取每个 API 的可运行示例。

## File Conversion

核心功能是将任何受支持的源文档转换为任何受支持的目标格式。所有转换均可在未安装 Microsoft Office、LibreOffice 或 Adobe Acrobat 的情况下完成。GroupDocs.Conversion 提供灵活的选项集，以自定义流水线。

### Convert specific document pages

转换整个文档、单独页面或页面范围。可以在 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 类上使用显式的 `pages` 列表或 `page_number` + `pages_count` 范围。查看 [Convert a Document to Another Format]() 以获取可运行的示例。

### Per-page file output

为每页生成一个输出文件 — 对于演示文稿、多页 PDF 和将文档渲染为图像非常有用。循环 `page_number` 属性并保持 `pages_count = 1`。查看 [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

当源文件以字节流形式出现且没有文件名时，GroupDocs.Conversion 会通过检查流头部自动检测格式。查看 [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically)。

### Load source document with extended options

每个加载选项类都公开特定格式的设置：

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

在运行流水线之前查询引擎支持的目标格式 — 可以在整个库层面、按扩展名或针对特定已加载文档进行查询。查看 [Get Possible Conversions]() 了解三种重载。

### Watermark the converted document

在转换时添加文字水印 — 控制颜色、大小、旋转、透明度以及背景/前景位置。查看 [Add a Watermark to Converted Document]().

### Convert files inside a container

打开 ZIP、RAR、7Z、OST 或 PST 容器，转换其内容，并在一次调用中写入合并的输出文档。查看 [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion 可以在不实际转换的情况下读取源文档的元数据 — 包括格式、页数或幻灯片数、作者、创建日期、尺寸、目录以及特定格式的详细信息。查看 [Getting Document Information]() 了解全部九种变体：

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Python 的 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 构造函数接受文件路径和二进制类文件对象两种形式，因此您可以从以下位置加载文档：

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

云存储（Amazon S3、Azure Blob Storage、Google Cloud Storage）通过将字节获取到 `BytesIO` 缓冲区并传递给 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 构造函数来工作。

## Logging and Diagnostics

通过 [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) 将 [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) 接入，以追踪转换流水线 — 加载器选择、转换开始与完成，以及引擎产生的任何警告。查看 [Logging and Diagnostics]().

## AI and LLM Integration

GroupDocs.Conversion 旨在成为 AI 文档流水线的一流构建块。`groupdocs-conversion-net` pip 包在 wheel 中附带 `AGENTS.md` 文件，以便 AI 编码助手能够自动发现 API 表面，且 GroupDocs 运行公共 [MCP server](https://docs.groupdocs.com/mcp) 供按需文档查询。请参阅 [Agents and LLM Integration]() 了解完整故事——包括如何将 GroupDocs.Conversion 与 GroupDocs.Markdown 链接以获得干净的 RAG 输入。

## On-Premise Deployment

没有云调用，没有出站网络流量，除操作系统已提供的内容外，没有第三方软件依赖。该 wheel 在 Windows 上是自包含的，并在 Linux 和 macOS 上随附其本机运行时库。请参阅 [System Requirements]() 获取可选本机包（ICU、fontconfig、Microsoft core fonts）的简短列表。
