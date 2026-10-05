---
title: "Kelas FinanceFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendefinisikan tipe dokumen keuangan."
type: docs
url: /id/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

Mendefinisikan tipe dokumen keuangan.

Menyertakan tipe berikut: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). Pelajari lebih lanjut tentang format keuangan di sini: https://docs.fileformat.com/finance/.

Tipe FinanceFileType menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | Menginisialisasi FinanceFileType untuk serialisasi. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Membandingkan objek saat ini dengan yang lain. (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Mengimplementasikan perbandingan kesetaraan yang didefinisikan oleh [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Mendapatkan FileType untuk ekstensi file yang diberikan. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Mengembalikan FileType untuk file_name yang ditentukan. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Mengembalikan FileType untuk aliran dokumen yang diberikan. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Menyediakan fungsi hash default. (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Representasi string dari tipe file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Deskripsi tipe file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Ekstensi file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Keluarga file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Format file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL adalah standar internasional terbuka untuk pelaporan bisnis digital yang banyak digunakan secara global. Ini adalah bahasa berbasis XML yang menggunakan elemen XBRL, yang dikenal sebagai tag, untuk menggambarkan setiap item data bisnis guna menyusun data untuk penyortiran dan analisis laporan. Pelajari lebih lanjut tentang format file ini di sini. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | Di dalam iXBRL, konten XBRL dibungkus dalam format file xHTML yang menggunakan tag XML. Seperti XBRL, merupakan elemen akar dari file iXBRL. Format XHTML merepresentasikan isinya sebagai kumpulan berbagai tipe dokumen dan modul. Semua file dalam XHTML berbasis format file XML dan mematuhi standar dokumen XML. Pelajari lebih lanjut tentang format file ini di sini. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange (OFX) adalah format aliran data untuk pertukaran informasi keuangan yang berkembang dari Open Financial Connectivity (OFC) milik Microsoft dan format file Open Exchange milik Intuit. Pelajari lebih lanjut tentang format file ini di sini. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipe file tidak diketahui (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Lihat Juga
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
