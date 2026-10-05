---
title: "Tambahkan Watermark ke Dokumen yang Dikonversi"
linkTitle: "Add a Watermark"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Tempelkan watermark teks pada setiap halaman dokumen yang dikonversi dengan GroupDocs.Conversion untuk Python via .NET — kontrol warna, ukuran, posisi, rotasi, transparansi, serta penempatan di latar depan atau latar belakang melalui WatermarkTextOptions."
type: docs
url: /id/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


Topik ini menjelaskan cara menambahkan watermark selama proses konversi menggunakan GroupDocs.Conversion untuk Python via .NET. Watermark dapat diterapkan pada dokumen saat dikonversi ke format lain, membantu melindungi konten dan memastikan dokumen dapat diidentifikasi.

Untuk mengaktifkan watermark, Anda dapat menggunakan atribut `watermark` dalam kelas [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) yang sesuai. Di bawah ini adalah kelas [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) yang didukung yang memungkinkan Anda mengonfigurasi watermark selama konversi:

Mencari kemampuan watermarking lanjutan? Meskipun GroupDocs.Conversion menawarkan watermarking dasar, Anda dapat menjelajahi [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) untuk solusi komprehensif dengan fitur yang ditingkatkan.

## Supported ConvertOptions Classes

Kelas [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) berikut yang menyediakan atribut `watermark`.

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).

## WatermarkTextOptions Class Attributes

Kelas [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) digunakan untuk mengonfigurasi tampilan watermark. Opsi berikut dapat dikonfigurasi untuk menambahkan watermark:

- **text**: The text to be used for the watermark.
- **font**: The font name used for the watermark text.
- **color**: The color of the watermark text.
- **width**: The width of the watermark.
- **height**: The height of the watermark.
- **top**: The top position of the watermark.
- **left**: The left position of the watermark.
- **rotation_angle**: The rotation angle of the watermark.
- **transparency**: The transparency level of the watermark.
- **background**: Specifies whether the watermark is stamped as a background. If set to `True`, the watermark is placed at the bottom. By default, it is `False`, and the watermark is placed on top of the content.

## Example: Add a Watermark to Converted Document

Contoh berikut menunjukkan cara mengonversi dokumen DOCX ke PDF dan menambahkan watermark:

{{< tabs \"example-1\">}}
{{< tab \"add_watermark_to_converted_document.py\" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Instansiasi Converter dengan dokumen input 
    with Converter("./professional-services.docx") as converter:
        # Atur opsi watermark
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Atur opsi konversi
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Lakukan konversi
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab \"professional-services.docx\" >}}

`professional-services.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"professional-services.pdf\" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
