---
title: "Ikhtisar Fitur"
linkTitle: "Features overview"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Fitur utama GroupDocs.Conversion untuk Python via .NET — lebih dari 10.000 pasangan format, pemilihan halaman, opsi muat/konversi, watermark, inspeksi dokumen, dan integrasi AI-pipeline."
type: docs
url: /id/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion untuk Python via .NET mengonversi dokumen antara **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, gambar, CAD, email, arsip, eBook, HTML, TeX, dan bahasa deskripsi halaman. Ia berjalan sepenuhnya di lingkungan lokal, tidak memerlukan instalasi Microsoft Office atau Adobe Acrobat, dan didistribusikan sebagai wheel pra-bangun pada Windows, Linux, dan macOS.

Lihat daftar lengkap [supported formats]() atau jelajahi [Developer Guide]() untuk contoh yang dapat dijalankan dari setiap permukaan API.

## File Conversion

Kemampuan inti adalah mengonversi dokumen sumber yang didukung apa pun ke format target yang didukung apa pun. Semua konversi dapat dilakukan tanpa Microsoft Office, LibreOffice, atau Adobe Acrobat terpasang. GroupDocs.Conversion menawarkan serangkaian opsi fleksibel untuk menyesuaikan pipeline.

### Convert specific document pages

Konversi seluruh dokumen, halaman individual, atau rentang halaman. Gunakan baik daftar `pages` eksplisit atau rentang `page_number` + `pages_count` pada kelas [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Lihat [Convert a Document to Another Format]() untuk contoh yang dapat dijalankan.

### Per-page file output

Hasilkan satu file output per halaman — berguna untuk presentasi, PDF multi-halaman, dan merender dokumen ke gambar. Loop atribut `page_number` sambil menjaga `pages_count = 1`. Lihat [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

Ketika file sumber datang sebagai aliran byte tanpa nama file, GroupDocs.Conversion mendeteksi format secara otomatis dengan memeriksa header aliran. Lihat [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Setiap kelas opsi muat menampilkan pengaturan spesifik format:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Kueri mesin untuk format target yang didukung sebelum menjalankan pipeline — pada tingkat seluruh perpustakaan, berdasarkan ekstensi, atau untuk dokumen yang dimuat tertentu. Lihat [Get Possible Conversions]() untuk tiga overload.

### Watermark the converted document

Tambahkan watermark teks saat mengonversi — kontrol warna, ukuran, rotasi, transparansi, dan penempatan latar belakang / latar depan. Lihat [Add a Watermark to Converted Document]().

### Convert files inside a container

Buka kontainer ZIP, RAR, 7Z, OST, atau PST, konversi isinya, dan tulis dokumen output terintegrasi dalam satu panggilan. Lihat [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion dapat membaca metadata dari dokumen sumber tanpa benar-benar mengonversinya — format, jumlah halaman atau slide, penulis, tanggal pembuatan, dimensi, daftar isi, dan detail spesifik format. Lihat [Getting Document Information]() untuk semua sembilan varian:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Konstruktor Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) menerima baik jalur file maupun objek berkas biner mirip file, sehingga Anda dapat memuat dokumen dari:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

Penyimpanan cloud (Amazon S3, Azure Blob Storage, Google Cloud Storage) bekerja dengan mengambil byte ke dalam buffer `BytesIO` dan meneruskannya ke konstruktor [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

## Logging and Diagnostics

Hubungkan sebuah [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) melalui [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) untuk melacak alur konversi — pemilihan pemuat, mulai dan selesai konversi, serta peringatan apa pun yang dihasilkan oleh mesin. Lihat [Logging and Diagnostics]().

## AI and LLM Integration

GroupDocs.Conversion dirancang sebagai blok bangunan kelas satu untuk pipeline dokumen AI. Paket pip `groupdocs-conversion-net` menyertakan file `AGENTS.md` di dalam wheel sehingga asisten penulisan kode AI dapat menemukan permukaan API secara otomatis, dan GroupDocs menjalankan [MCP server](https://docs.groupdocs.com/mcp) publik untuk pencarian dokumentasi sesuai permintaan. Lihat [Agents and LLM Integration]() untuk cerita lengkap — termasuk cara menghubungkan GroupDocs.Conversion dengan GroupDocs.Markdown untuk input RAG yang bersih.

## On-Premise Deployment

Tidak ada panggilan cloud, tidak ada lalu lintas jaringan keluar, tidak ada ketergantungan perangkat lunak pihak ketiga selain yang sudah disediakan oleh OS. Wheel bersifat mandiri di Windows dan menyertakan pustaka runtime native sendiri di Linux dan macOS. Lihat [System Requirements]() untuk daftar singkat paket native opsional (ICU, fontconfig, Microsoft core fonts).
