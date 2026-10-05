---
title: "Konversi Dokumen ke Format Lain"
linkTitle: "Convert to Another Format"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Konversi satu dokumen dari satu format ke format lain, secara opsional memilih halaman tertentu atau rentang halaman menggunakan atribut pages / page_number / pages_count pada ConvertOptions dengan GroupDocs.Conversion untuk Python via .NET."
type: docs
url: /id/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Topik dokumentasi ini mencakup konversi satu dokumen ke format lain, di mana hanya satu dokumen yang dihasilkan sebagai output. Diagram berikut menggambarkan proses mengonversi file dari satu format ke format lain:

flowchart LR
%% Nodes
A["Input Document (e.g. DOCX)"]
B["Conversion"]
C["Converted Document (e.g. PDF)"]

%% Koneksi tepi antara node
A --> B --> C

Untuk mengonversi dan menyimpan dokumen, gunakan metode kelas berikut [`Converter`](/conversion/python-net/groupdocs.conversion/converter/):

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

Daftar berikut dari kelas [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) dapat digunakan untuk mengonversi dokumen ke format output tunggal tertentu:

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **EmailConvertOptions** – Options for converting to [Email]() formats (e.g., EML, MSG).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **ProjectManagementConvertOptions** – Options for converting to [Project Management]() formats (e.g., MPP).
- **GisConvertOptions** – Options for converting to [GIS]() formats.
- **FontConvertOptions** – Options for converting to [Font]() formats (e.g., TTF, OTF).
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).
- **CompressionConvertOptions** – Options for converting to [Compression]() formats (e.g., ZIP).
- **NoConvertOptions** – A special option class that instructs the converter to copy the source document without any modifications.

### Example 1: Convert a Document to Another Format

Contoh berikut menunjukkan cara mengonversi file DOCX ke PDF:

{{< tabs \"example-1\">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Instansiasi Converter dengan dokumen input 
    with Converter("./business-plan.docx") as converter:
        # Instansiasi opsi konversi untuk menentukan format output
        pdf_convert_options = PdfConvertOptions()
        
        # Konversi dokumen input ke PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

Secara default, setiap kelas [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) memiliki format target default masing-masing. Misalnya, format output default untuk [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) adalah [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

Untuk mengatur format output yang berbeda dalam keluarga format, gunakan properti `format`. Contoh berikut menunjukkan cara menentukan format target sebagai `TXT` saat mengonversi file `DOCX`:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Instansiasi Converter dengan dokumen input 
    with Converter("./business-plan.docx") as converter:
        # Instansiasi opsi konversi untuk menentukan format output, secara default adalah DOCX
        word_convert_options = WordProcessingConvertOptions()
        # Ubah format output dalam keluarga format dari DOCX ke TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Konversi dokumen input ke TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "business-plan.txt" >}}
```text
﻿HOME BASED

PROFESSIONAL SERVICES

Business Plan

[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/specify_output_format/business-plan.txt)
{{< /tab >}}
{{< /tabs >}}

## Specify Document Pages to Convert

Cari tahu cara mendapatkan jumlah halaman dokumen dalam topik dokumentasi [Getting Document Information]().

Untuk mengonversi halaman dokumen tertentu, Anda dapat menggunakan kelas [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) berikut, yang menyediakan atribut `pages`, `page_number`, dan `pages_count`. Opsi-opsi ini memungkinkan Anda menentukan halaman individual atau rentang halaman untuk dikonversi.

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

### Example 1: Convert Specific Document Pages to Another Format

Anda dapat menentukan halaman dokumen mana yang ingin Anda konversi, seperti yang ditunjukkan pada contoh berikut:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Instansiasi Converter dengan dokumen input 
    with Converter("./business-plan.docx") as converter:
        # Instansiasi opsi konversi untuk menentukan format output
        pdf_convert_options = PdfConvertOptions()
        # Tentukan halaman dokumen yang akan dikonversi
        pdf_convert_options.pages = [1, 3, 5]

        # Konversi halaman yang ditentukan dari dokumen input ke PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

Sebagai alternatif, Anda dapat menentukan sejumlah halaman berurutan untuk dikonversi, seperti yang ditunjukkan pada contoh berikut:

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Instansiasi Converter dengan dokumen input 
    with Converter("./business-plan.docx") as converter:
        # Instansiasi opsi konversi untuk menentukan format output
        pdf_convert_options = PdfConvertOptions()
        # Tentukan halaman mulai dan jumlah halaman yang akan dikonversi
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Konversi rentang halaman yang ditentukan dalam dokumen ke PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
