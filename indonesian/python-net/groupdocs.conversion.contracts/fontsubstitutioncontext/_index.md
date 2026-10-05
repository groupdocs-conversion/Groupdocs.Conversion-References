---
title: "kelas FontSubstitutionContext"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menjelaskan satu substitusi font yang terjadi saat memuat atau merender dokumen sumber."
type: docs
url: /id/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Menjelaskan satu substitusi font yang terjadi saat memuat atau merender dokumen sumber.

Instansi diteruskan ke [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

Tipe FontSubstitutionContext menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Menginisialisasi FontSubstitutionContext baru. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | Nama font yang dirujuk oleh dokumen sumber tetapi tidak tersedia bagi pipeline konversi. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | Pesan substitusi persis seperti yang dilaporkan oleh pipeline konversi, verbatim dan tidak diparse. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | Nama file dari dokumen sumber yang sedang dikonversi. Ketika sumber disediakan sebagai aliran yang bukan `io.RawIOBase`, ini berisi pengidentifikasi yang dihasilkan alih-alih nama file yang sebenarnya. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | Nama font yang digunakan sebagai pengganti. Mungkin None untuk dokumen yang mesin melaporkan substitusi hanya sebagai teks deskriptif — dalam kasus tersebut baca [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### Lihat Juga
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
