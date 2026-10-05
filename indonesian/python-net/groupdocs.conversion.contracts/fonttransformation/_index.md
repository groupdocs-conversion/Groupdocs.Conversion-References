---
title: "Kelas FontTransformation"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menjelaskan konfigurasi transformasi font termasuk atribut font, yang diterapkan setelah pemuatan dokumen dan substitusi font."
type: docs
url: /id/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Menjelaskan konfigurasi transformasi font termasuk atribut font, yang diterapkan setelah pemuatan dokumen dan substitusi font.

Tipe FontTransformation menampilkan anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Membuat transformasi font dengan pencocokan font yang tepat (ukuran dan gaya harus cocok). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Membuat transformasi font hanya berdasarkan nama, mencocokkan ukuran dan gaya apa pun, dengan font pengganti mempertahankan ukuran dan gaya font asli. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Membuat transformasi font dengan opsi pencocokan fleksibel. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Menentukan apakah dua instance objek sama. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Berfungsi sebagai fungsi hash default. (diturunkan dari [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | Properti menunjukkan apakah ukuran font apa pun untuk nama font asli cocok (true) atau hanya ukuran font tepat yang ditentukan dalam `OriginalFont` yang cocok (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | Properti menentukan apakah gaya font apa pun (tebal, miring, bergaris bawah) dari font asli cocok (True) atau gaya font tepat yang ditentukan dalam `OriginalFont` diperlukan (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | Spesifikasi font asli untuk dicocokkan dan diganti. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | Spesifikasi font pengganti. |

### Lihat Juga
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
