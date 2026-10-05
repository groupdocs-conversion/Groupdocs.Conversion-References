---
title: "Kelas ProjectManagementFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendefinisikan format file Project yang dibuat oleh perangkat lunak Manajemen Proyek seperti Microsoft Project, Primavera P6, dll."
type: docs
url: /id/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

Mendefinisikan format file Project yang dibuat oleh perangkat lunak Manajemen Proyek seperti Microsoft Project, Primavera P6, dll.

File proyek adalah kumpulan tugas, sumber daya, dan penjadwalannya untuk menghasilkan output yang dapat diukur berupa produk atau layanan. Dokumen manajemen proyek. Menyertakan tipe file berikut: [`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/), [`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/), [`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/). Pelajari lebih lanjut tentang format Manajemen Proyek di sini: https://wiki.fileformat.com/project-management.

Tipe ProjectManagementFileType menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | Menginisialisasi ProjectManagementFileType untuk serialisasi. |

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
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | File templat Microsoft Project, berisi informasi dasar dan struktur serta pengaturan dokumen untuk membuat file .MPP. Pelajari lebih lanjut tentang format file ini di sini. |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP adalah file data Microsoft Project yang menyimpan informasi terkait manajemen proyek secara terintegrasi. Pelajari lebih lanjut tentang format file ini di sini. |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange File Format adalah format file ASCII untuk mentransfer informasi proyek antara Microsoft Project (MSP) dan aplikasi lain yang mendukung format file MPX seperti Primavera Project Planner, Sciforma, dan Timerline Precision Estimating. Pelajari lebih lanjut tentang format file ini di sini. |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | Format file XER adalah format file proyek proprietari yang digunakan oleh aplikasi perencanaan dan manajemen proyek Primavera P6. Pelajari lebih lanjut tentang format file ini di sini. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipe file tidak diketahui (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Lihat Juga
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
