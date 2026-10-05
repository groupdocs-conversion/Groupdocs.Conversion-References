---
title: "properti keep_image_stream_open"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Properti ini menentukan apakah konverter mempertahankan stream gambar tetap terbuka setelah konversi."
type: docs
url: /id/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

Properti ini menentukan apakah konverter mempertahankan stream gambar tetap terbuka setelah konversi.

Ketika False (default), konverter menutup [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) setelah menulis — idiomatik untuk penggantian `io.RawIOBase` yang harus dibuang ke disk. Setel ke True untuk menjaga aliran tetap terbuka setelah konversi selesai (umum untuk `io.BytesIO` yang ingin Anda baca sendiri); pemanggil kemudian bertanggung jawab atas pembuangan.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### Lihat Juga
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
