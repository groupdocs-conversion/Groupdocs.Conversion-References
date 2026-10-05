---
title: "Kelas ConverterSettings"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendefinisikan pengaturan untuk menyesuaikan perilaku Converter."
type: docs
url: /id/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Mendefinisikan pengaturan untuk menyesuaikan perilaku Converter.

Tipe ConverterSettings menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Menginisialisasi instance baru dari ConverterSettings dengan nilai default. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | Implementasi cache yang digunakan untuk menyimpan hasil konversi. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | Jalur direktori font khusus. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | Implementasi listener konverter yang digunakan untuk memantau status dan kemajuan konversi, dengan callback Started, Progress, dan Completed yang diteruskan ke [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), dan [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) selama konstruksi [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | Implementasi logger yang digunakan untuk mencatat proses konversi. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | Penangan peristiwa untuk kompresi selesai. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | Penangan peristiwa yang dipanggil ketika konversi per halaman gagal. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | Penangan peristiwa yang dipanggil ketika konversi gagal. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | Konverter memindai direktori font secara rekursif ketika diatur ke True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | Folder sementara yang digunakan untuk konversi. |

### Contoh

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Lihat Juga
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
