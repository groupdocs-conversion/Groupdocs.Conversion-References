---
title: "기능 개요"
linkTitle: "Features overview"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "Python용 GroupDocs.Conversion (.NET 기반)의 주요 기능 — 10,000개 이상의 형식 쌍, 페이지 선택, 로드/변환 옵션, 워터마크, 문서 검사 및 AI 파이프라인 통합."
type: docs
url: /ko/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

Python용 GroupDocs.Conversion (.NET 기반)은 **10,000+ format pairs** 사이에서 문서를 변환합니다 — Microsoft Office, PDF, OpenDocument, 이미지, CAD, 이메일, 압축 파일, 전자책, HTML, TeX 및 페이지 기술 언어 등. 완전히 온프레미스에서 실행되며 Microsoft Office나 Adobe Acrobat 설치가 필요 없고, Windows, Linux, macOS용 사전 구축 휠 형태로 제공됩니다.

전체 [supported formats]() 목록을 확인하거나, 모든 API 영역에 대한 실행 가능한 예제를 보려면 [Developer Guide]()를 살펴보세요.

## File Conversion

핵심 기능은 지원되는 모든 원본 문서를 지원되는 대상 형식으로 변환하는 것입니다. Microsoft Office, LibreOffice 또는 Adobe Acrobat이 설치되지 않아도 모든 변환이 가능합니다. GroupDocs.Conversion은 파이프라인을 맞춤 설정할 수 있는 유연한 옵션을 제공합니다.

### Convert specific document pages

전체 문서, 개별 페이지 또는 페이지 범위를 변환합니다. 명시적인 `pages` 목록이나 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) 클래스의 `page_number` + `pages_count` 범위를 사용할 수 있습니다. 실행 가능한 예제는 [Convert a Document to Another Format]()를 참고하세요.

### Per-page file output

페이지당 하나의 출력 파일을 생성합니다 — 프레젠테이션, 다중 페이지 PDF, 문서를 이미지로 렌더링할 때 유용합니다. `pages_count = 1`을 유지하면서 `page_number` 속성을 반복합니다. 자세한 내용은 [Convert a Document to Multiple Page Files]()를 참고하세요.

### Auto-detect source document format

소스 파일이 파일 이름 없이 바이트 스트림으로 제공될 경우, GroupDocs.Conversion은 스트림 헤더를 검사하여 형식을 자동으로 감지합니다. 자세한 내용은 [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically)를 참고하세요.

### Load source document with extended options

각 로드 옵션 클래스는 형식별 설정을 제공합니다:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

파이프라인을 실행하기 전에 엔진에 지원되는 대상 형식을 조회합니다 — 전체 라이브러리 수준, 확장자별, 또는 특정 로드된 문서별로. 세 가지 오버로드에 대한 내용은 [Get Possible Conversions]()를 참고하세요.

### Watermark the converted document

변환 중에 텍스트 워터마크를 추가합니다 — 색상, 크기, 회전, 투명도 및 배경/전경 배치를 제어합니다. 자세한 내용은 [Add a Watermark to Converted Document]()를 참고하세요.

### Convert files inside a container

ZIP, RAR, 7Z, OST 또는 PST 컨테이너를 열어 내용을 변환하고, 한 번의 호출로 통합된 출력 문서를 작성합니다. 자세한 내용은 [Convert Files Within Document Containers]()를 참고하세요.

## Document Information Extraction

GroupDocs.Conversion은 실제로 변환하지 않고도 소스 문서에서 메타데이터를 읽을 수 있습니다 — 형식, 페이지 또는 슬라이드 수, 작성자, 생성 날짜, 차원, 목차 및 형식별 세부 정보 등. 모든 9가지 변형에 대한 내용은 [Getting Document Information]()를 참고하세요:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 생성자는 파일 경로와 바이너리 파일‑유사 객체를 모두 받아들여, 다음과 같은 위치에서 문서를 로드할 수 있습니다:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

클라우드 스토리지(Amazon S3, Azure Blob Storage, Google Cloud Storage)는 바이트를 `BytesIO` 버퍼로 가져와 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 생성자에 전달하는 방식으로 작동합니다.

## Logging and Diagnostics

[`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/)를 [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)와 연결하여 변환 파이프라인을 추적합니다 — 로더 선택, 변환 시작 및 완료, 엔진에서 발생한 경고 등. 자세한 내용은 [Logging and Diagnostics]()를 참고하세요.

## AI and LLM Integration

GroupDocs.Conversion은 AI 문서 파이프라인을 위한 1급 빌딩 블록으로 설계되었습니다. `groupdocs-conversion-net` pip 패키지는 휠 내부에 `AGENTS.md` 파일을 포함하여 AI 코딩 어시스턴트가 API 표면을 자동으로 탐색할 수 있게 하며, GroupDocs는 온디맨드 문서 조회를 위해 공개 [MCP server](https://docs.groupdocs.com/mcp)를 운영합니다. 전체 이야기는 [Agents and LLM Integration]()을 참조하십시오 — 여기에는 GroupDocs.Conversion을 GroupDocs.Markdown과 연결하여 깔끔한 RAG 입력을 만드는 방법이 포함됩니다.

## On-Premise Deployment

클라우드 호출 없음, 외부 네트워크 트래픽 없음, 운영 체제에서 이미 제공하는 것 외의 서드파티 소프트웨어 종속성 없음. 휠은 Windows에서 자체 포함되어 있으며 Linux와 macOS에서는 자체 네이티브 런타임 라이브러리를 포함합니다. 선택적 네이티브 패키지(예: ICU, fontconfig, Microsoft core fonts)의 간단한 목록은 [System Requirements]()를 참조하십시오.
