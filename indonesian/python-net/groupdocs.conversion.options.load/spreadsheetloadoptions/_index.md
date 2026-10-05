---
title: "Kelas SpreadsheetLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menyediakan opsi untuk memuat dokumen Spreadsheet."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/
is_root: false
weight: 440
---


## SpreadsheetLoadOptions class

Menyediakan opsi untuk memuat dokumen Spreadsheet.

Tipe SpreadsheetLoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/__init__/) | Menginisialisasi sebuah instance baru dari [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/). |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Mengkloning instance saat ini. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Menentukan apakah dua instance objek sama. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Berfungsi sebagai fungsi hash default. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | Properti ini menentukan apakah semua konten kolom dari sebuah lembar ditampilkan pada satu halaman dalam hasil. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Baris-baris secara otomatis disesuaikan saat konversi. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | Properti ini menentukan apakah pembatasan file Excel diperiksa saat memodifikasi objek terkait sel. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_built_in_document_properties/) | Properti ClearBuiltInDocumentProperties menentukan apakah properti dokumen bawaan dibersihkan saat memuat spreadsheet. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_custom_document_properties/) | Properti ClearCustomDocumentProperties. |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Jumlah kolom per halaman yang digunakan untuk membagi lembar kerja menjadi halaman; defaultnya 0, yang menonaktifkan paginasi. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owned/) | Properti ini mengimplementasikan [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) dan defaultnya False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owner/) | Properti yang mengimplementasikan [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/). Defaultnya True. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Rentang yang akan dikonversi saat mengonversi ke format non‑spreadsheet, misalnya "D1:F8". |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Informasi budaya sistem yang digunakan saat file dimuat. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/default_font/) | Font default untuk dokumen spreadsheet. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/depth/) | Kedalaman opsi pemuatan kontainer dokumen. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/font_substitutes/) | Pengganti font yang digunakan saat mengonversi dokumen spreadsheet. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/format/) | Tipe berkas dokumen masukan. |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | Properti ini menunjukkan apakah akan mengabaikan kesalahan perhitungan formula. Kesalahan dapat berupa fungsi yang tidak didukung, tautan eksternal, dll. Defaultnya False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/margin_settings/) | Pengaturan margin. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | Properti ini menunjukkan apakah konten setiap lembar dikonversi menjadi satu halaman dalam dokumen PDF. Nilai defaultnya True. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | Konversi dioptimalkan untuk ukuran file yang lebih kecil daripada kualitas cetak ketika diatur ke True saat mengonversi ke PDF. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Kata sandi yang digunakan untuk membuka proteksi dokumen yang dilindungi. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | Flag yang menunjukkan apakah struktur dokumen harus dipertahankan saat mengonversi ke PDF (default adalah False). |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Cara komentar dicetak bersama lembar. Defaultnya PrintNoComments. |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Folder font direset sebelum memuat dokumen. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Jumlah baris per halaman yang digunakan untuk membagi lembar kerja menjadi halaman, dengan default 0 yang berarti tidak ada paginasi. |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | Daftar indeks lembar untuk dikonversi. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Nama lembar untuk dikonversi. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Opsi untuk menampilkan garis kisi saat mengonversi file Excel. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Opsi untuk menampilkan lembar tersembunyi saat mengonversi file Excel. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/size_settings/) | Pengaturan ukuran, seperti yang didefinisikan oleh [`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/). |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Pengaturan yang melewati baris dan kolom kosong saat mengonversi. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_external_resources/) | Properti ini mengimplementasikan [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | Properti menentukan apakah footer dilewati saat mengonversi dokumen spreadsheet. Default: False. |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | Opsi untuk melewati header saat mengonversi dokumen spreadsheet. Default: False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/whitelisted_resources/) | Sumber daya yang masuk daftar putih seperti yang didefinisikan oleh [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Lihat Juga
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
