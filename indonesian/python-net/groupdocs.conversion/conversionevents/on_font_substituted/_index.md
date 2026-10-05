---
title: "properti on_font_substituted"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Peristiwa yang dipicu ketika font yang dirujuk oleh dokumen sumber tidak tersedia dan diganti (baik oleh aturan FontSubstitute yang disediakan pelanggan, oleh font default yang dikonfigurasi, atau oleh …"
type: docs
url: /id/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

Peristiwa dipicu ketika font yang dirujuk oleh dokumen sumber tidak tersedia dan digantikan (baik oleh aturan [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) yang disediakan pelanggan, oleh font default yang dikonfigurasi, atau oleh fallback internal pipeline konversi).

Peristiwa ini didedupikasi per `(SourceFileName, OriginalFontName)` dalam satu panggilan `Converter.Convert(...)` — pelanggan menerima paling banyak satu notifikasi per font yang hilang per dokumen sumber. Dipicu secara sinkron pada thread konversi. Tidak dipicu untuk konversi gambar.

Untuk dokumen presentasi, substitusi font hanya terdeteksi di Windows, karena mesin menyelesaikannya melalui pencocokan font spesifik platform yang tidak tersedia di sistem operasi lain.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### Lihat Juga
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
