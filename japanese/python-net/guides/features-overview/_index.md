---
title: "機能概要"
linkTitle: "Features overview"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "GroupDocs.Conversion for Python via .NET の主な機能 — 10,000 以上のフォーマットペア、ページ選択、ロード/変換オプション、透かし、ドキュメント検査、AI パイプライン統合。"
type: docs
url: /ja/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion for Python via .NET は、ドキュメントを **10,000+ format pairs** の間で変換します — Microsoft Office、PDF、OpenDocument、画像、CAD、メール、アーカイブ、eBooks、HTML、TeX、ページ記述言語。完全にオンプレミスで実行され、Microsoft Office や Adobe Acrobat のインストールは不要で、Windows、Linux、macOS 用の事前構築済みホイールとして提供されます。

[supported formats]() の完全なリストをご覧いただくか、[Developer Guide]() を参照して、すべての API の実行例をご確認ください。

## File Conversion

コア機能は、サポートされている任意のソースドキュメントをサポートされている任意のターゲット形式に変換することです。Microsoft Office、LibreOffice、Adobe Acrobat をインストールせずにすべての変換が可能です。GroupDocs.Conversion は、パイプラインをカスタマイズするための柔軟なオプションセットを提供します。

### Convert specific document pages

ドキュメント全体、個別ページ、またはページ範囲を変換します。明示的な `pages` リストまたは `page_number` + `pages_count` の範囲を [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) クラスで使用します。実行例については [Convert a Document to Another Format]() を参照してください。

### Per-page file output

ページごとに1つの出力ファイルを生成します — プレゼンテーション、マルチページ PDF、ドキュメントの画像へのレンダリングに便利です。`pages_count = 1` を維持しながら `page_number` 属性をループします。[Convert a Document to Multiple Page Files]() を参照してください。

### Auto-detect source document format

ソースファイルがファイル名なしのバイトストリームとして提供される場合、GroupDocs.Conversion はストリームヘッダーを検査して自動的にフォーマットを検出します。[Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically) を参照してください。

### Load source document with extended options

すべてのロードオプションクラスは、フォーマット固有の設定を公開します：

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

パイプラインを実行する前に、エンジンにサポートされているターゲットフォーマットを問い合わせます — ライブラリ全体レベル、拡張子別、または特定のロード済みドキュメントごとに。3つのオーバーロードについては [Get Possible Conversions]() を参照してください。

### Watermark the converted document

変換中にテキスト透かしを追加します — 色、サイズ、回転、透明度、背景/前景の配置を制御します。[Add a Watermark to Converted Document]() を参照してください。

### Convert files inside a container

ZIP、RAR、7Z、OST、または PST コンテナを開き、内容を変換し、単一の呼び出しで統合された出力ドキュメントを書き込みます。[Convert Files Within Document Containers]() を参照してください。

## Document Information Extraction

GroupDocs.Conversion は、実際に変換せずにソースドキュメントからメタデータを読み取ることができます — フォーマット、ページまたはスライド数、作者、作成日、寸法、目次、フォーマット固有の詳細。すべての9つのバリエーションについては [Getting Document Information]() を参照してください：

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Python の [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) コンストラクタは、ファイルパスとバイナリファイルライクオブジェクトの両方を受け入れるため、次の場所からドキュメントをロードできます：

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

クラウドストレージ（Amazon S3、Azure Blob Storage、Google Cloud Storage）は、バイトを `BytesIO` バッファに取得し、それを [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) コンストラクタに渡すことで機能します。

## Logging and Diagnostics

`[`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) を [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) 経由で接続し、変換パイプライン（ローダー選択、変換開始と完了、エンジンからの警告）を追跡します。[Logging and Diagnostics]() を参照してください。

## AI and LLM Integration

GroupDocs.Conversion は、AI ドキュメント パイプライン向けの一流の構成要素として設計されています。`groupdocs-conversion-net` pip パッケージは、wheel 内に `AGENTS.md` ファイルを同梱しており、AI コーディング アシスタントが API の概要を自動的に検出できるようにします。また、GroupDocs はオンデマンドのドキュメント検索用にパブリックな [MCP server](https://docs.groupdocs.com/mcp) を運用しています。全容については [Agents and LLM Integration]() を参照してください — その中で GroupDocs.Conversion と GroupDocs.Markdown を連携させ、クリーンな RAG 入力を実現する方法が説明されています。

## On-Premise Deployment

クラウド呼び出しなし、外部ネットワークトラフィックなし、OS が既に提供しているもの以外のサードパーティ ソフトウェア依存はありません。wheel は Windows で自己完結型であり、Linux と macOS では独自のネイティブランタイム ライブラリを同梱しています。オプションのネイティブ パッケージ（ICU、fontconfig、Microsoft core fonts）の簡易リストについては [System Requirements]() を参照してください。
