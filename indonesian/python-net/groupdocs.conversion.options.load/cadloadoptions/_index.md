---
title: "Kelas CadLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menyediakan opsi untuk memuat dokumen CAD."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/cadloadoptions/
is_root: false
weight: 60
---


## CadLoadOptions class

Menyediakan opsi untuk memuat dokumen CAD.

Tipe CadLoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/__init__/) | Menginisialisasi instance baru dari kelas [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/). |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Menentukan apakah dua instance objek sama. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Berfungsi sebagai fungsi hash default. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/background_color/) | Warna latar belakang. |
| [ctb_sources](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/ctb_sources/) | Sumber CTB. |
| [draw_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_color/) | Warna latar depan. |
| [draw_type](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_type/) | Jenis gambar. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/format/) | Tipe berkas dokumen masukan. |
| [layout_names](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) | Nama tata letak yang akan dikonversi. |
| [layout_scope](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) | Ruang lingkup tata letak yang menentukan ruang gambar mana yang dikonversi. Defaultnya adalah [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), yang tidak membatasi konversi. Diabaikan ketika [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) disediakan, karena nama tata letak eksplisit selalu menang. Nilai `None` diperlakukan sebagai [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/). |

### Lihat Juga
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
