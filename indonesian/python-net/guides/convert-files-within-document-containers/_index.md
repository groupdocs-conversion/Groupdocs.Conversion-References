---
title: "Konversi File dalam Kontainer Dokumen"
linkTitle: "Convert Archives and Containers"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Buka format kontainer ZIP, RAR, 7Z, OST, PST, dan format lainnya, konversi isinya, dan tulis dokumen output yang terkonsolidasi dalam satu panggilan Converter.convert() dengan GroupDocs.Conversion untuk Python via .NET."
type: docs
url: /id/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


Topik ini membahas cara mengonversi file yang tertanam dalam kontainer dokumen, seperti file terkompresi atau terpaket, menjadi file output terpisah. Diagram berikut menggambarkan proses mengekstrak dan mengonversi file dalam sebuah kontainer dokumen:

flowchart LR
%% Nodes
A["Kontainer Dokumen"]
B["Ekstraksi"]
C["Konversi"]
D["File Terkonversi 1"]
E["File Terkonversi 2"]
F["File Terkonversi N"]

%% Koneksi tepi antara node
A --> B --> C --> D
C --> E
C --> F

Proses Ekstraksi dan Konversi dilakukan dalam satu panggilan ke metode `convert(file_path, convert_options)` dari kelas [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). GroupDocs.Conversion membuka kontainer, mengonversi file yang ada di dalamnya, dan menulis dokumen output yang terkonsolidasi.

## Document Container File Types

Tipe file berikut dianggap sebagai kontainer dokumen:

### Email and Outlook

- **EML** - Email Message File.
- **EMLX** - Apple Mail Email File.
- **MSG** - Microsoft Outlook Message File.
- **OST** - Outlook Offline Data File.
- **PST** - Outlook Personal Information Store File.

### PDF

- **PDF** - PDF files that contain embedded resources.

### Word Processing

- **DOC** - The older Microsoft Word binary format.
- **DOCX** - The modern Word format.
- **DOT and DOTX** - Word template files.
- **RTF** - Rich Text Format.

### Compression

- **7Z** - 7-Zip Compressed File.
- **BZ2** - Bzip2 Compressed File.
- **CAB** - Windows Cabinet File.
- **CPIO** - CPIO Compressed File.
- **GZ** - Gnu Zipped Archive.
- **GZIP** - Gzip Compressed File.
- **LZ** - Lzip Compressed File.
- **LZMA** - LZMA Compressed File.
- **RAR** - RAR Compressed Archive.
- **TAR** - Consolidated Unix File Archive.
- **XZ** - Xz Compressed File.
- **Z** - Unix Compressed File.
- **ZIP** - ZIP Compressed File.

## Example: Convert Files Within Document Container

Contoh berikut menunjukkan cara mengonversi isi arsip ZIP menjadi satu PDF yang terkonsolidasi:

{{< tabs \"example-1\">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Instansiasi Converter dengan kontainer dokumen input
    with Converter("./compressed.zip") as converter:
        # Instansiasi opsi konversi
        pdf_convert_options = PdfConvertOptions()

        # Ekstrak arsip, konversi file yang terdapat di dalamnya, dan simpan PDF yang terkonsolidasi
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) untuk mengunduhnya.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
