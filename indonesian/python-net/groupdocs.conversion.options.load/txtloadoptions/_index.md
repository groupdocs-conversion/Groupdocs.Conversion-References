---
title: "Kelas TxtLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Opsi untuk memuat dokumen Txt."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Opsi untuk memuat dokumen Txt.

Konfigurasi Font untuk Teks Biasa:

Karena file TXT tidak mengandung informasi font, gunakan DefaultTextFont untuk menentukan font yang akan merender konten teks biasa selama konversi.

Tipe TxtLoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Menginisialisasi sebuah instance baru dari [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

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
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | Font yang akan digunakan saat merender konten teks biasa selama konversi. Default: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | Properti ini menentukan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi. Nilai default adalah True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | Encoding yang digunakan saat memuat dokumen Txt. Bisa None. Default adalah None. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | Tipe berkas dokumen masukan. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | Opsi yang disarankan untuk menangani spasi di awal. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | Pengaturan margin, sebagaimana didefinisikan oleh [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | Opsi ukuran halaman untuk memuat dokumen TXT. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | Opsi yang disarankan untuk menangani spasi akhir. Nilai default adalah [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### Lihat Juga
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
