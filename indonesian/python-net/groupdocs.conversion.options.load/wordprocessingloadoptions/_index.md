---
title: "Kelas WordProcessingLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menyediakan opsi untuk memuat dokumen WordProcessing."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

Menyediakan opsi untuk memuat dokumen WordProcessing.

Pipeline Pemrosesan Font:

Tahap 1 - Substitusi Font (selama pemuatan dokumen):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

Tahap 2 - Penggantian Font (setelah pemuatan dokumen):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

Tipe WordProcessingLoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | Menginisialisasi sebuah instance baru dari [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

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
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | Properti auto_detect_rtl_direction menentukan apakah paragraf dan run dengan teks yang sebagian besar dari kanan ke kiri memiliki flag bidi yang diperbaiki sebelum konversi. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | Opsi bookmark. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | Flag yang menunjukkan apakah properti dokumen bawaan dibersihkan saat memuat dokumen pengolahan Word. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | Properti ClearCustomDocumentProperties. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | Mode tampilan komentar menentukan bagaimana komentar harus ditampilkan dalam dokumen output. Default adalah `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | Properti ini mengimplementasikan [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). Default adalah False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | Flag convert_owner menunjukkan apakah pemilik dokumen harus dikonversi. Default adalah True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | Font default untuk dokumen WordProcessing. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | Kedalaman opsi pemuatan kontainer dokumen. Default adalah 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | Properti embed_true_type_fonts menentukan apakah font TrueType disematkan dalam dokumen output. Default adalah True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | Properti ini mengaktifkan substitusi otomatis font yang hilang berdasarkan FontConfig sistem. Default adalah False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | Flag yang mengaktifkan substitusi otomatis font yang hilang berdasarkan FontInfo dalam dokumen. Default: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | Properti ini menunjukkan apakah font yang hilang secara otomatis disubstitusi berdasarkan nama font. Default: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | Substitusi font yang digunakan saat mengonversi dokumen WordProcessing. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | Transformasi font yang diterapkan setelah pemuatan dokumen dan substitusi font selesai, memungkinkan modifikasi font apa pun dalam dokumen, termasuk yang berhasil dimuat. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | Tipe berkas dokumen masukan. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | Properti hide_word_tracked_changes menyembunyikan markup dan pelacakan perubahan untuk dokumen Word. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | Opsi hyphenation untuk dokumen WordProcessing. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | Properti keep_date_field_original_value menentukan apakah nilai asli bidang tanggal dipertahankan. Default adalah False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | Pengaturan margin. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | Flag pembuatan penomoran halaman untuk dokumen yang dikonversi (default: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | Password untuk membuka proteksi dokumen yang dilindungi. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | Flag yang menunjukkan apakah struktur dokumen harus dipertahankan saat mengonversi ke PDF (default adalah False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | Properti ini menunjukkan apakah bidang formulir Microsoft Word dipertahankan sebagai bidang formulir dalam PDF yang dihasilkan atau dikonversi menjadi teks. Defaultnya adalah False. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | Nama lengkap pemberi komentar ditampilkan dalam komentar ketika diatur ke True. Defaultnya adalah False. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | Pengaturan ukuran untuk dokumen WordProcessing ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | Flag yang menentukan apakah sumber daya eksternal dilewati saat memuat dokumen. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | Opsi untuk memperbarui bidang setelah memuat. Default: False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | Tata letak halaman diperbarui setelah memuat. Default: False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | Properti ini menunjukkan apakah akan menggunakan text shaper untuk tampilan kerning yang lebih baik. Defaultnya adalah False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | Sumber daya yang masuk daftar putih untuk memuat konten eksternal, mengimplementasikan [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Contoh

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
Panduan tugas yang menggunakan `WordProcessingLoadOptions`:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Lihat Juga
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
