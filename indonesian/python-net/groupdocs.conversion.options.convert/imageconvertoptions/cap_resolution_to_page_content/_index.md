---
title: "properti cap_resolution_to_page_content"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Properti ini membatasi resolusi render PDF per halaman ke resolusi raster asli halaman, mencegah render pada DPI yang lebih tinggi daripada gambar yang disematkan dan menghasilkan halaman dengan resolusi aslinya (lebih kecil)…"
type: docs
url: /id/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

Properti ini membatasi resolusi render PDF per halaman ke resolusi raster asli halaman, mencegah render pada DPI yang lebih tinggi daripada gambar yang disematkan dan menghasilkan halaman dengan dimensi piksel dan DPI asli (lebih kecil) pada output akhir.

Hanya halaman yang didominasi gambar (pemindaian) yang terpengaruh; halaman dengan teks atau konten vektor tidak pernah dilunakkan dan dihasilkan pada DPI yang diminta. Batas ini diabaikan ketika output eksplisit [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) atau [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) diatur. Nilai defaultnya adalah False (tidak ada pembatasan; setiap halaman dirender dan dihasilkan pada DPI yang diminta).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### Lihat Juga
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
