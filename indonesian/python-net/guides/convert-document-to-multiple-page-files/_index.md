---
title: "Konversi Dokumen ke Berkas Multi Halaman"
linkTitle: "Convert Document To Multiple"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /id/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Konversi Dokumen ke Berkas Multi Halaman
linkTitle: Konversi ke Beberapa File
weight: 3
description: "Render setiap halaman dari dokumen multi-halaman ke file output masing-masing — loop page_number dengan pages_count=1 dan Converter.convert() untuk menghasilkan satu PNG, PDF, atau gambar per halaman dengan GroupDocs.Conversion untuk Python via .NET."
keywords: konversi ke beberapa file, output per halaman, page_number, pages_count, page loop, convert presentation pages, convert PDF pages to PNG, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion untuk Python via .NET
hideChildren: false
toc: true
---

Topik dokumentasi ini mencakup konversi satu dokumen multi-halaman menjadi file halaman terpisah. Diagram berikut menggambarkan proses mengonversi file multi-halaman menjadi halaman terpisah:

flowchart LR
%% Nodes
A["Dokumen Input"]
B["Conversion"]
C["Halaman Terkonversi 1"]
D["Halaman Terkonversi 2"]
E["Halaman Terkonversi N"]

%% Koneksi tepi antara node
A --> B --> C
B --> D
B --> E

Untuk mengonversi dokumen menjadi file per halaman, gunakan metode `Converter.convert(file_path, convert_options)` bersama dengan atribut `page_number` dan `pages_count` pada kelas [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) yang didukung:

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

Untuk menghasilkan satu file output per halaman, lakukan loop dari `1` hingga `converter.get_document_info().pages_count`, memperbarui `page_number` pada setiap iterasi dan menulis ke jalur output yang berbeda. Menetapkan `pages_count = 1` memastikan setiap panggilan menghasilkan satu halaman.

## Supported ConvertOptions Classes

Kelas [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) berikut mengekspos atribut `page_number` dan `pages_count` yang digunakan dalam topik ini:

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).

## Example 1: Convert All Pages of a Document and Save Output to a Folder

Contoh berikut menunjukkan cara mengonversi setiap slide dalam presentasi PPTX menjadi gambar PNG dan menyimpan gambar output ke folder yang ditentukan.
 
Templat nama file untuk file output adalah `converted-page-{page number}.{output file extension}`. Dalam contoh ini, slide pertama akan disimpan sebagai `converted-page-1.png`.

{{< tabs \"example-1\">}}
{{< tab "convert_all_document_pages.py" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Buat instance Converter dengan dokumen input
    with Converter("./basic-presentation.pptx") as converter:
        # Tentukan jumlah total halaman dalam dokumen sumber
        pages_count = converter.get_document_info().pages_count

        # Instansiasi opsi konversi sekali dan gunakan kembali di dalam loop
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Konversi setiap halaman ke file PNG terpisah
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "convert-all-document-pages-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (26 KB)
converted-pages/converted-page-10.png (81 KB)
converted-pages/converted-page-11.png (67 KB)
converted-pages/converted-page-12.png (70 KB)
converted-pages/converted-page-13.png (36 KB)
converted-pages/converted-page-2.png (34 KB)
converted-pages/converted-page-3.png (797 KB)
converted-pages/converted-page-4.png (1262 KB)
converted-pages/converted-page-5.png (75 KB)
converted-pages/converted-page-6.png (33 KB)
[TRUNCATED] (13 files total)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_all_document_pages/convert-all-document-pages-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Convert a Specific Page and Save Output to a File

Cari tahu cara mendapatkan jumlah halaman dokumen dalam topik dokumentasi [Getting Document Information]().

Contoh berikut menunjukkan cara mengonversi slide tertentu dalam presentasi PPTX dan menyimpannya sebagai file terpisah.

{{< tabs "example-2">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Buat instance Converter dengan dokumen input
    with Converter("./basic-presentation.pptx") as converter:
        # Instansiasi opsi konversi
        png_convert_options = ImageConvertOptions()
        # Tentukan format output sebagai PNG
        png_convert_options.format = ImageFileType.PNG

        # Tentukan halaman tunggal yang akan dikonversi
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Simpan halaman yang dikonversi ke sebuah file
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Cari tahu cara mendapatkan jumlah halaman dokumen dalam topik dokumentasi [Getting Document Information]().

Jika Anda memerlukan halaman yang dikonversi sebagai buffer dalam memori (misalnya, untuk diteruskan ke API lain tanpa menyentuh sistem file setelahnya), konversi halaman ke file terlebih dahulu lalu bacalah ke dalam objek `BytesIO`:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_page_to_stream.py" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # Buat instance Converter dengan dokumen input
    with Converter("./basic-presentation.pptx") as converter:
        # Instansiasi opsi konversi
        png_convert_options = ImageConvertOptions()
        # Tentukan format output sebagai PNG
        png_convert_options.format = ImageFileType.PNG

        # Tentukan halaman tunggal yang akan dikonversi
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Konversi dan simpan halaman ke file di disk
        converter.convert(output_file, png_convert_options)

    # Muat halaman yang dikonversi ke dalam aliran dalam memori untuk penggunaan selanjutnya
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream sekarang berisi byte PNG dan dapat diteruskan ke siapa pun yang membutuhkannya
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
