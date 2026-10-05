---
title: "Kelas ImageConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mewakili opsi untuk mengonversi dokumen ke tipe file gambar."
type: docs
url: /id/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

Mewakili opsi untuk mengonversi dokumen ke tipe file gambar.

Tipe ImageConvertOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | Menginisialisasi sebuah instance baru dari ImageConvertOptions. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | Warna latar belakang yang digunakan bila didukung oleh format sumber. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | Penyesuaian kecerahan gambar. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | Properti ini membatasi resolusi render PDF per halaman ke resolusi raster asli halaman, mencegah render pada DPI yang lebih tinggi daripada gambar yang disematkan dan menghasilkan halaman dengan dimensi piksel dan DPI asli (lebih kecil) pada output akhir. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | Penyesuaian kontras yang diterapkan pada gambar. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | Area pemotongan gambar raster setelah konversi. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | Mode pembalikan gambar. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | Tipe file yang diinginkan untuk mengonversi dokumen masukan. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | Penyesuaian gamma gambar. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | Opsi yang menunjukkan apakah gambar akan dikonversi ke skala abu-abu. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | Tinggi gambar yang diinginkan setelah konversi. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | Resolusi horizontal gambar yang diinginkan setelah konversi; default ke resolusi file input atau 96 dpi. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | Opsi konversi khusus JPEG. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | Batas bawah per-sumbu yang diterapkan pada DPI render yang dibatasi ketika [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) diaktifkan. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | Nomor halaman untuk memulai konversi. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | Daftar indeks halaman yang akan dikonversi. Harus ditentukan untuk mengonversi halaman tertentu. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | Jumlah halaman yang akan dikonversi mulai dari `PageNumber`. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | Opsi konversi khusus PSD. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | Sudut rotasi gambar. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Opsi konversi khusus Tiff. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | Properti UsePdf. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | Resolusi vertikal gambar yang diinginkan setelah konversi. Resolusi default adalah resolusi file input atau 96 dpi. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | Opsi khusus watermark. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | Opsi konversi khusus WebP. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | Lebar gambar yang diinginkan setelah konversi. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Guides
Panduan tugas yang menggunakan `ImageConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### Lihat Juga
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
