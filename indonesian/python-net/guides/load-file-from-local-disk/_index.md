---
title: "Muat File Dari Disk Lokal"
linkTitle: "Load From Local Disk"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Instansiasi kelas Converter dengan jalur file absolut atau relatif untuk mengonversi dokumen yang disimpan di sistem file lokal menggunakan GroupDocs.Conversion untuk Python via .NET."
type: docs
url: /id/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


Untuk memuat file sumber dari disk lokal Anda, Anda dapat menggunakan konstruktor kelas [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) di GroupDocs.Conversion. API menawarkan beberapa overload, memungkinkan fleksibilitas untuk berbagai pengaturan dan opsi:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Setiap konstruktor memerlukan parameter `filePath`, yang menentukan jalur ke file sumber. Anda dapat menentukan ini sebagai jalur absolut atau relatif. Perhatikan bahwa jika jalur file yang ditentukan tidak ada, sebuah pengecualian akan dilempar.

GroupDocs.Conversion akan mengakses file hanya ketika sebuah tindakan (mis., konversi) dilakukan menggunakan instance kelas [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Contoh Python berikut menunjukkan cara memuat file dari disk lokal dan mengonversinya ke PDF:

{{< tabs \"code-example\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Tentukan lokasi file sumber
    converter = Converter("./business-plan.docx")
    
    # Tentukan lokasi file output dan opsi konversi
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Konversi dan simpan ke jalur output
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion menentukan jenis file berdasarkan ekstensi. Jika ekstensi file tidak ditetapkan, GroupDocs.Conversion akan mencoba mendeteksi jenis file secara otomatis. Bergantung pada jenis file dan ukuran, deteksi jenis file otomatis mengonsumsi sumber daya tambahan, seperti memori dan waktu CPU. Oleh karena itu, kami menyarankan memastikan bahwa file memiliki ekstensi yang benar atau menggunakan konstruktor kelas Converter yang menerima opsi pemuatan.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Lihat [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) untuk detail lebih lanjut tentang penggunaan opsi pemuatan dan overload konstruktor lainnya.
