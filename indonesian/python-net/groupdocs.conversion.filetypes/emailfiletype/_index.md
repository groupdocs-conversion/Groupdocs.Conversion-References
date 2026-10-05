---
title: "Kelas EmailFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendefinisikan format file email yang digunakan oleh aplikasi email untuk menyimpan pesan, lampiran, folder, buku alamat, dan data lainnya."
type: docs
url: /id/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

Mendefinisikan format file email yang digunakan oleh aplikasi email untuk menyimpan pesan, lampiran, folder, buku alamat, dan data lainnya.

Menyertakan tipe file berikut:
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

Pelajari lebih lanjut tentang format email di https://wiki.fileformat.com/email.

Tipe EmailFileType mengungkapkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | Menginisialisasi EmailFileType baru untuk serialisasi. |

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
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya. Pelajari lebih lanjut tentang format file ini di sini. |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya. Hampir semua klien email mendukung format file ini karena kepatuhannya terhadap Standar Format Pesan Internet RFC-822. Pelajari lebih lanjut tentang format file ini di sini. |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | Format file EMLX diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email. Pelajari lebih lanjut tentang format file ini di sini. |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF (Virtual Card Format) atau vCard adalah format file digital untuk menyimpan informasi kontak. Format ini banyak digunakan untuk pertukaran data di antara aplikasi pertukaran informasi populer. Pelajari lebih lanjut tentang format file ini di sini. |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | Format file MBox adalah istilah umum yang mewakili wadah untuk kumpulan pesan surat elektronik. Pesan-pesan disimpan di dalam wadah bersama lampirannya. Pelajari lebih lanjut tentang format file ini di sini. |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | File dengan ekstensi .PST mewakili Outlook Personal Storage Files (juga disebut Personal Storage Table) yang menyimpan berbagai informasi pengguna. Pelajari lebih lanjut tentang format file ini di sini. |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST atau Offline Storage Files mewakili data kotak surat pengguna dalam mode offline pada mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook. Pelajari lebih lanjut tentang format file ini di sini. |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | File dengan ekstensi .olm adalah file Microsoft Outlook untuk Sistem Operasi Mac. File OLM menyimpan pesan email, jurnal, data kalender, dan jenis data aplikasi lainnya. Ini mirip dengan file PST yang digunakan oleh Outlook pada Sistem Operasi Windows. Namun, file OLM yang dibuat oleh Outlook untuk Mac tidak dapat dibuka di Outlook untuk Windows. Pelajari lebih lanjut tentang format file ini di sini. |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | Format file ICS (iCalendar) digunakan untuk merepresentasikan dan menukar informasi kalender serta penjadwalan seperti acara, tugas, dan data bebas/sibuk. Pelajari lebih lanjut tentang format file ini di sini. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipe file tidak diketahui (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Lihat Juga
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
