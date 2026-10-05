---
title: "Kelas EmailLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menyediakan opsi untuk memuat dokumen Email."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/emailloadoptions/
is_root: false
weight: 130
---


## EmailLoadOptions class

Menyediakan opsi untuk memuat dokumen Email.

Tipe EmailLoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/__init__/) | Menginisialisasi instance baru dari kelas [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/). |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/clone/) | Mengkloning instance saat ini. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Menentukan apakah dua instance objek sama. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Berfungsi sebagai fungsi hash default. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/attachment_icons/) | Daftar ikon lampiran, yang dapat disesuaikan untuk menyediakan ikon khusus bagi berbagai jenis file. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owned/) | Properti mengimplementasikan [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). Default adalah True. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owner/) | Properti convert_owner mengimplementasikan [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/). Default adalah True. |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/custom_css_style/) | Gaya CSS khusus, mengimplementasikan [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/). |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/default_font/) | Font default untuk dokumen email. Font ini akan digunakan jika font yang diperlukan tidak ada. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/depth/) | Kedalaman opsi pemuatan kontainer dokumen. |
| [display_attachments](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_attachments/) | Opsi untuk menampilkan atau menyembunyikan lampiran di header. Default: True. |
| [display_bcc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_bcc_email_address/) | Opsi untuk menampilkan atau menyembunyikan alamat email Bcc. Default: False. |
| [display_cc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_cc_email_address/) | Opsi untuk menampilkan atau menyembunyikan alamat email \"Cc\", defaultnya False. |
| [display_email_addresses](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_email_addresses/) | Opsi untuk mengontrol apakah alamat email ditampilkan bersamaan dengan nama. Default: True. |
| [display_from_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_from_email_address/) | Opsi untuk menampilkan atau menyembunyikan alamat email \"from\". Default: True. |
| [display_header](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_header/) | Opsi untuk menampilkan atau menyembunyikan header email. Default: True. |
| [display_sent](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_sent/) | Opsi untuk menampilkan atau menyembunyikan tanggal/waktu terkirim di header. Default: True. |
| [display_subject](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_subject/) | Opsi untuk menampilkan atau menyembunyikan subjek di header. Default: True. |
| [display_to_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_to_email_address/) | Opsi untuk menampilkan atau menyembunyikan alamat email \"to\". Default: True. |
| [field_text_map](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/field_text_map/) | Pemetaan antara pesan email [`EmailField`](/conversion/python-net/groupdocs.conversion.options.load/emailfield/) dan representasi teks bidang. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/font_substitutes/) | Daftar substitusi font. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/format/) | Tipe berkas dokumen masukan. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/margin_settings/) | Pengaturan margin. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/orientation_settings/) | Pengaturan orientasi. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/page_layout_options/) | Properti ini mengimplementasikan [`IPageLayoutOptions.page_layout_options`](/conversion/python-net/groupdocs.conversion.options.load/ipagelayoutoptions/page_layout_options/). |
| [preserve_original_date](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/preserve_original_date/) | Properti ini menentukan apakah mempertahankan string header tanggal asli dalam pesan email saat menyimpan. Nilai default adalah True. |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/resource_loading_timeout/) | Batas waktu untuk memuat sumber daya eksternal. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/size_settings/) | Pengaturan ukuran halaman untuk operasi pemuatan email. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/skip_external_resources/) | Properti yang mengimplementasikan [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [time_zone_offset](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/time_zone_offset/) | Offset Waktu Universal Terkoordinasi (UTC) untuk tanggal pesan. |
| [use_default_attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/use_default_attachment_icons/) | Bendera yang menunjukkan apakah ikon lampiran default digunakan (default: True). |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/whitelisted_resources/) | Properti ini mengimplementasikan [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Lihat Juga
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
