---
title: "kelas CadDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Berisi metadata dokumen Cad."
type: docs
url: /id/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Berisi metadata dokumen Cad.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Tanpa menyebutkan secara eksplisit [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) lembar-lembar tersebut adalah ruang model, yang selalu dapat dipetakan dan oleh karena itu selalu menjadi lembar, ditambah setiap tata letak ruang kertas yang pengaturan halaman tersimpan memiliki lebar dan tinggi positif, dipersempit oleh [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). Nama tata letak eksplisit menang langsung: lembar-lembar kemudian menjadi nama yang diberikan gambar, dicocokkan secara berurutan, tanpa ruang lingkup maupun pengaturan halaman menyaringnya.

Untuk DWF, set halaman yang dipublikasikan dilaporkan. Hitungan satu di bawah satu adalah nol, dilaporkan ketika ruang lingkup yang diminta tidak cocok dengan lembar manapun dari gambar yang menawarkan satu: metadata masih menggambarkan gambar, dan nol berarti ruang lingkup tidak memilih apa pun alih-alih membuat pemanggil gagal yang menanyakan apa yang dimiliki gambar. Konversi dengan opsi muatan yang sama gagal.

Hitungan tersebut oleh karena itu bukan ukuran dari [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/), yang mencantumkan setiap konfigurasi plot yang dibawa gambar termasuk yang tidak dapat dipublikasikan dari lembar manapun, dan tidak memprediksi berapa banyak halaman yang dihasilkan oleh konversi tertentu.

Tipe CadDocumentInfo menampilkan anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | Tanggal pembuatan dokumen. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | Format dokumen. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | Tinggi dokumen CAD. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | Lapisan dalam dokumen. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | Tata letak dalam dokumen. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | Jumlah halaman dokumen. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | Enumerable semua properti yang dapat diambil untuk info dokumen saat ini. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | Ukuran dokumen dalam byte. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | Lebar dokumen CAD. |

### Lihat Juga
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
