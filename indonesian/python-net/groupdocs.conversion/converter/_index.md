---
title: "kelas Converter"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mewakili kelas utama yang mengontrol proses konversi dokumen."
type: docs
url: /id/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

Mewakili kelas utama yang mengontrol proses konversi dokumen.

Tipe Converter menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Menginisialisasi sebuah instance baru dari Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | Menginisialisasi sebuah instance baru [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | Menginisialisasi sebuah instance baru [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | Menginisialisasi Converter baru dengan peristiwa konversi eksplisit. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | Menginisialisasi sebuah instance Converter baru dengan peristiwa konversi eksplisit. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | Menginisialisasi sebuah instance Converter baru. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | Menginisialisasi sebuah instance baru [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | Menginisialisasi instance baru kelas [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | Menginisialisasi Converter baru dengan peristiwa konversi eksplisit. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | Menginisialisasi Converter baru dengan peristiwa konversi eksplisit. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Mengonversi dokumen sumber dan menyimpan dokumen yang telah dikonversi halaman demi halaman. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Mengonversi dokumen sumber dan menyimpan dokumen yang telah dikonversi halaman demi halaman. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Mengonversi dokumen sumber dan menyimpan dokumen yang telah dikonversi halaman demi halaman. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Mengonversi dokumen sumber dan menyimpan dokumen yang telah dikonversi halaman demi halaman. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | Melepaskan sumber daya. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | Mendapatkan semua konversi yang didukung. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | Mengambil konversi yang mungkin untuk dokumen sumber. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | Mendapatkan konversi yang didukung untuk ekstensi dokumen yang diberikan. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | Memeriksa apakah dokumen sumber dilindungi kata sandi. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Panduan tugas yang menggunakan `Converter`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### Lihat Juga
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
