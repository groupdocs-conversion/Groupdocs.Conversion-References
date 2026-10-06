---
title: "Özellikler Genel Bakışı"
linkTitle: "Features overview"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "GroupDocs.Conversion for Python via .NET'in temel özellikleri — **10,000+ format pairs**, sayfa seçimi, yükleme/dönüştürme seçenekleri, filigranlar, belge incelemesi ve AI-pipeline entegrasyonu."
type: docs
url: /tr/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion for Python via .NET, belgeleri **10,000+ format pairs** arasında dönüştürür — Microsoft Office, PDF, OpenDocument, görüntüler, CAD, e-posta, arşivler, eKitaplar, HTML, TeX ve sayfa‑tanımlama dilleri. Tamamen yerinde çalışır, Microsoft Office veya Adobe Acrobat kurulumu gerektirmez ve Windows, Linux ve macOS üzerinde önceden oluşturulmuş bir tekerlek (wheel) olarak sunulur.

Tam listeyi [desteklenen formatlar]() içinde görüntüleyin veya her API yüzeyi için çalıştırılabilir örnekleri görmek üzere [Geliştirici Kılavuzu]()na göz atın.

## File Conversion

Temel yetenek, desteklenen herhangi bir kaynak belgeyi desteklenen herhangi bir hedef formata dönüştürmektir. Tüm dönüşümler, Microsoft Office, LibreOffice veya Adobe Acrobat yüklü olmadan mümkündür. GroupDocs.Conversion, pipeline'ı özelleştirmek için esnek bir seçenek seti sunar.

### Convert specific document pages

Tam belgeleri, tek tek sayfaları veya sayfa aralıklarını dönüştürün. Ya açık bir `pages` listesi ya da [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) sınıfındaki `page_number` + `pages_count` aralığını kullanın. Çalıştırılabilir örnekler için [Bir Belgeyi Başka Bir Formata Dönüştür]() bölümüne bakın.

### Per-page file output

Sayfa başına bir çıktı dosyası üretin — sunumlar, çok sayfalı PDF'ler ve belgeleri görüntülere dönüştürmek için faydalıdır. `pages_count = 1` iken `page_number` özniteliğini döngüye alın. Çalıştırılabilir örnekler için [Bir Belgeyi Çoklu Sayfa Dosyalarına Dönüştür]() bölümüne bakın.

### Auto-detect source document format

Bir kaynak dosya dosya adı olmadan bir bayt akışı olarak geldiğinde, GroupDocs.Conversion akış başlığını inceleyerek formatı otomatik olarak algılar. Bkz. [Akıştan Dosya Yükle](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Her yükleme seçeneği sınıfı, format‑özel ayarları ortaya çıkarır:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Bir pipeline çalıştırmadan önce motoru desteklenen hedef formatlar için sorgulayın — tüm kütüphane düzeyinde, uzantıya göre veya belirli bir yüklenmiş belge için. Üç aşırı yükleme için [Olası Dönüşümler Al]() bölümüne bakın.

### Watermark the converted document

Dönüştürürken bir metin filigranı ekleyin — renk, boyut, dönüş, şeffaflık ve arka plan/ön plan yerleşimini kontrol edin. Çalıştırılabilir örnekler için [Dönüştürülmüş Belgeye Filigran Ekle]() bölümüne bakın.

### Convert files inside a container

ZIP, RAR, 7Z, OST veya PST konteynerlerini açın, içeriği dönüştürün ve tek bir çağrıda birleşik bir çıktı belgesi yazın. Çalıştırılabilir örnekler için [Belge Kapsayıcıları İçindeki Dosyaları Dönüştür]() bölümüne bakın.

## Document Information Extraction

GroupDocs.Conversion, bir kaynak belgeden gerçek bir dönüşüm yapmadan meta verileri okuyabilir — format, sayfa veya slayt sayısı, yazar, oluşturma tarihi, boyutlar, içindekiler tablosu ve format‑özel detaylar. Tüm dokuz varyant için [Belge Bilgilerini Alma]() bölümüne bakın:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) yapıcı, hem bir dosya yolunu hem de ikili dosya benzeri bir nesneyi kabul eder, böylece belgeleri şuradan yükleyebilirsiniz:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

Bulut depolama (Amazon S3, Azure Blob Storage, Google Cloud Storage), baytları bir `BytesIO` tamponuna alarak ve bunu [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) yapıcısına geçirerek çalışır.

## Logging and Diagnostics

Bir [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) aracılığıyla [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) bağlayarak dönüşüm hattını izleyin — yükleyici seçimi, dönüşüm başlangıcı ve tamamlanması, ve motor tarafından verilen tüm uyarılar. Bakınız [Logging and Diagnostics]().

## AI and LLM Integration

GroupDocs.Conversion, AI belge işlem hatları için birinci sınıf bir yapı taşı olacak şekilde tasarlanmıştır. `groupdocs-conversion-net` pip paketi, tekerleğin içinde bir `AGENTS.md` dosyası gönderir, böylece AI kodlama asistanları API yüzeyini otomatik olarak keşfedebilir ve GroupDocs, isteğe bağlı belge aramaları için genel bir [MCP server](https://docs.groupdocs.com/mcp) çalıştırır. Tam hikaye için [Agents and LLM Integration]() bölümüne bakın — GroupDocs.Conversion'ı GroupDocs.Markdown ile temiz RAG girişi için nasıl zincirleyeceğinizi de içerir.

## On-Premise Deployment

Bulut çağrısı yok, dışa giden ağ trafiği yok, işletim sisteminin zaten sağladığının ötesinde üçüncü taraf yazılım bağımlılıkları yok. Tekerlek Windows'ta kendi içinde bulunur ve Linux ve macOS'ta kendi yerel çalışma zamanı kütüphanelerini gönderir. Opsiyonel yerel paketlerin (ICU, fontconfig, Microsoft core fonts) kısa listesi için [System Requirements]() bölümüne bakın.
