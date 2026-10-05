---
title: "Kelas TsvLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mewakili opsi untuk memuat dokumen TSV."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/tsvloadoptions/
is_root: false
weight: 480
---


## TsvLoadOptions class

Mewakili opsi untuk memuat dokumen TSV.

Tipe TsvLoadOptions memperlihatkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/__init__/) | Menginisialisasi instance baru dari [`TsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/). |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Mengkloning instance saat ini. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Menentukan apakah dua instance objek sama. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Berfungsi sebagai fungsi hash default. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_built_in_document_properties/) | Properti ini menghapus properti metadata bawaan dari dokumen. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_custom_document_properties/) | Properti ini menghapus properti metadata khusus dari dokumen. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owned/) | Opsi untuk mengontrol apakah dokumen yang dimiliki dalam kontainer dokumen harus dikonversi. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owner/) | Opsi untuk mengontrol apakah kontainer dokumen itu sendiri harus dikonversi; jika true, kontainer akan menjadi dokumen pertama yang dikonversi. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/default_font/) | Font yang akan digunakan jika sebuah font tidak tersedia. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/depth/) | Opsi untuk mengontrol berapa banyak tingkat kedalaman yang akan dilakukan konversi. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/font_substitutes/) | Pengganti font. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/format/) | Tipe berkas dokumen masukan. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/margin_settings/) | Pengaturan margin halaman. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/size_settings/) | Pengaturan ukuran halaman. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/skip_external_resources/) | Properti ini menentukan apakah sumber daya eksternal dimuat; jika True, semua sumber daya eksternal tidak akan dimuat kecuali yang ada dalam daftar [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). Default: True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/whitelisted_resources/) | Sumber daya eksternal yang akan selalu dimuat. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | Properti ini menentukan apakah semua konten kolom dari sebuah lembar dirender pada satu halaman dalam hasil. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Baris-baris secara otomatis disesuaikan saat mengonversi. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | Properti ini menentukan apakah pembatasan file Excel diperiksa saat memodifikasi objek terkait sel. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Jumlah kolom per halaman yang digunakan untuk membagi lembar kerja menjadi halaman; defaultnya 0, yang menonaktifkan paginasi. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Rentang yang akan dikonversi saat mengonversi ke format non‑spreadsheet, misalnya "D1:F8". (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Info budaya sistem yang digunakan saat file dimuat. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | Properti ini menunjukkan apakah akan mengabaikan kesalahan perhitungan formula. Kesalahan dapat berupa fungsi yang tidak didukung, tautan eksternal, dll. Nilai default adalah False. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | Properti ini menunjukkan apakah konten setiap lembar diubah menjadi satu halaman dalam dokumen PDF. Nilai default adalah True. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | Konversi dioptimalkan untuk ukuran file yang lebih kecil daripada kualitas cetak ketika diatur ke True saat mengonversi ke PDF. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Kata sandi yang digunakan untuk membuka proteksi dokumen yang dilindungi. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | Bendera yang menunjukkan apakah struktur dokumen harus dipertahankan saat mengonversi ke PDF (default adalah False). (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Cara komentar dicetak bersama lembar. Default adalah PrintNoComments. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Folder font direset sebelum memuat dokumen. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Jumlah baris per halaman yang digunakan untuk membagi lembar kerja menjadi halaman, dengan default 0 yang berarti tidak ada paginasi. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | Daftar indeks lembar yang akan dikonversi. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Nama lembar yang akan dikonversi. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Opsi untuk menampilkan garis kisi saat mengonversi file Excel. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Opsi untuk menampilkan lembar tersembunyi saat mengonversi file Excel. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Pengaturan yang melewatkan baris dan kolom kosong saat mengonversi. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | Properti ini menentukan apakah footer dilewati saat mengonversi dokumen spreadsheet. Default: False. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | Opsi untuk melewatkan header saat mengonversi dokumen spreadsheet. Default: False. (diturunkan dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |

### Lihat Juga
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
