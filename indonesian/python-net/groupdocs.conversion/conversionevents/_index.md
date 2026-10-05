---
title: "Kelas ConversionEvents"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menggabungkan penangkap peristiwa siklus hidup konversi."
type: docs
url: /id/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Menggabungkan penangkap peristiwa siklus hidup konversi.

Berikan sebuah instance ke parameter `events` konstruktor [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) atau ke metode `WithEvents` yang bersifat fluent.

Lebih pilih ini dibandingkan properti penangan individual [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/), yang sudah usang.

Tipe ConversionEvents menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | Peristiwa yang dipicu ketika kompresi output konversi selesai. Hanya dipanggil pada build yang menyertakan pipeline kompresi (LIB_ZIP). |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | Peristiwa yang dipicu sekali ketika proses konversi selesai, terlepas dari keberhasilan atau kegagalan. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | Progres konversi sebagai persentase (0–100), dipicu secara berkala. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | Peristiwa yang dipicu sekali pada awal proses konversi, sebelum dokumen apa pun diproses. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | Peristiwa dipicu sekali per konversi seluruh dokumen yang selesai dengan sukses. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | Peristiwa dipicu sekali per konversi seluruh dokumen yang gagal. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | Peristiwa dipicu ketika font yang dirujuk oleh dokumen sumber tidak tersedia dan digantikan (baik oleh aturan [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) yang disediakan pelanggan, oleh font default yang dikonfigurasi, atau oleh fallback internal pipeline konversi). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | Peristiwa dipicu sekali per halaman ketika konversi per halaman selesai dengan sukses. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | Peristiwa dipicu sekali per halaman ketika konversi per halaman gagal. |

### Lihat Juga
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
