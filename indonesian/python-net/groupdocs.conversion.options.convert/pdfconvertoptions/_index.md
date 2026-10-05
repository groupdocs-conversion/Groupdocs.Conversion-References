---
title: "Kelas PdfConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Opsi untuk konversi ke tipe file PDF."
type: docs
url: /id/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

Opsi untuk konversi ke tipe file PDF.

Tipe PdfConvertOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | Menginisialisasi sebuah instance baru [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | DPI halaman yang diinginkan setelah konversi. Resolusi default adalah 96 dpi. |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | Properti ini menentukan apakah file font lengkap disematkan ke dalam PDF alih-alih subset. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | Ukuran halaman cadangan. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | Tipe file yang diinginkan untuk mengonversi dokumen masukan. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | Pengaturan margin yang diterapkan selama konversi PDF. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | Pengaturan orientasi. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | Nomor halaman untuk memulai konversi. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | Daftar indeks halaman yang akan dikonversi; tentukan untuk mengonversi halaman tertentu. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | Jumlah halaman yang akan dikonversi mulai dari `page_number`. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | Kata sandi yang digunakan untuk melindungi dokumen yang dikonversi. |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | Opsi konversi khusus PDF. |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | Mode ubah ukuran menentukan bagaimana konten harus diskalakan ketika ukuran halaman diubah. Default adalah AlignTopLeft (tanpa skala). |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | Rotasi halaman. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | Pengaturan ukuran halaman yang digunakan selama konversi PDF. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | Opsi khusus watermark. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Panduan tugas yang menggunakan `PdfConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Lihat Juga
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
