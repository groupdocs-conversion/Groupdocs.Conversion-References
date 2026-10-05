---
title: "Panduan Memulai Cepat"
linkTitle: "Quick Start Guide"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Siapkan lingkungan virtual, instal groupdocs-conversion-net, dan jalankan tiga contoh minimal — DOCX → PDF, PDF → PNG per halaman, dan ZIP → PDF terintegrasi — dalam waktu kurang dari lima menit."
type: docs
url: /id/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Panduan ini memberikan ikhtisar singkat tentang cara menyiapkan dan mulai menggunakan GroupDocs.Conversion untuk Python melalui .NET. Perpustakaan ini memungkinkan pengembang mengonversi antara berbagai format file (mis., DOCX, PDF, PNG) dengan konfigurasi minimal.

## Prerequisites

Untuk melanjutkan, pastikan Anda memiliki:

1. Lingkungan **Configured** seperti yang dijelaskan dalam topik [System Requirements]().
2. **Optionally** Anda dapat [Dapatkan Lisensi Sementara](https://purchase.groupdocs.com/temporary-license/) untuk menguji semua fitur produk.

## Set Up Your Development Environment

Untuk praktik terbaik, gunakan lingkungan virtual untuk mengelola dependensi dalam aplikasi Python. Pelajari lebih lanjut tentang lingkungan virtual di topik dokumentasi [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Buat lingkungan virtual:

{{< tabs "example1">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Aktifkan lingkungan virtual:

{{< tabs "example2">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-conversion-net` Package

Setelah mengaktifkan lingkungan virtual, jalankan perintah berikut di terminal Anda untuk menginstal versi terbaru paket:

{{< tabs "example3">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

Pastikan paket terinstal dengan sukses. Anda harus melihat pesan

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

Untuk menguji perpustakaan dengan cepat, mari konversi file DOCX ke PDF. Anda juga dapat mengunduh aplikasi yang akan kami bangun [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip).

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Dapatkan jalur absolut file lisensi
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Buat Lisensi dan atur jalurnya
        license = License()
        license.set_license(license_path)

    # Muat file DOCX
    with Converter("./business-plan.docx") as converter:
        # Buat opsi konversi
        pdf_convert_options = PdfConvertOptions()

        # Konversi DOCX ke PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Pohon folder Anda seharusnya terlihat mirip dengan struktur direktori berikut:

```Directory
📂 demo-app
 ├──convert_docx_to_pdf.py
 ├──business-plan.docx
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

Setelah menjalankan aplikasi, Anda dapat menonaktifkan lingkungan virtual dengan menjalankan `deactivate` atau menutup shell Anda.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

Dalam contoh ini kami akan mengonversi halaman dokumen PDF ke PNG. Anda dapat mengunduh aplikasi yang akan kami bangun [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip).

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Dapatkan jalur absolut file lisensi
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Buat Lisensi dan atur jalurnya
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Muat dokumen PDF
    with Converter("./annual-review.pdf") as converter:
        # Tentukan jumlah total halaman dalam dokumen sumber
        pages_count = converter.get_document_info().pages_count

        # Buat opsi konversi dan gunakan kembali di dalam loop
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Konversi setiap halaman ke file PNG terpisah
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "convert-pdf-pages-to-png-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (1148 KB)
converted-pages/converted-page-2.png (89 KB)
converted-pages/converted-page-3.png (83 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_pdf_pages_to_png/convert-pdf-pages-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Pohon folder Anda seharusnya terlihat mirip dengan struktur direktori berikut:

```Directory
📂 demo-app
 ├──annual-review.pdf
 ├──convert_pdf_pages_to_png.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_pdf_pages_to_png">}}
{{< tab "Windows" >}}
```ps
py convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

Setelah menjalankan aplikasi, Anda dapat menonaktifkan lingkungan virtual dengan menjalankan `deactivate` atau menutup shell Anda.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

Dalam contoh ini kami akan mengonversi isi arsip ZIP ke PDF. GroupDocs.Conversion membuka arsip, mengonversi file di dalamnya, dan menghasilkan satu PDF terintegrasi yang berisi semua dokumen yang telah dikonversi. Anda dapat mengunduh aplikasi yang akan kami bangun [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip).

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Dapatkan jalur absolut file lisensi
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Buat Lisensi dan atur jalurnya
        license = License()
        license.set_license(license_path)

    # Muat file ZIP
    with Converter("./compressed.zip") as converter:
        # Buat opsi konversi
        pdf_convert_options = PdfConvertOptions()

        # Ekstrak arsip, konversi isinya, dan simpan PDF yang terkonsolidasi
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) untuk mengunduhnya.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

Pohon folder Anda seharusnya terlihat mirip dengan struktur direktori berikut:

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs \"run_the_app_convert_files_in_archive\">}}
{{< tab "Windows" >}}
```ps
py convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< /tabs >}}

Setelah menjalankan aplikasi, Anda dapat menonaktifkan lingkungan virtual dengan menjalankan `deactivate` atau menutup shell Anda.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

Setelah menyelesaikan dasar-dasar, jelajahi sumber daya tambahan untuk meningkatkan penggunaan Anda:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
