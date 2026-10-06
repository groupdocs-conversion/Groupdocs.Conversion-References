---
title: "Belge Kapları İçindeki Dosyaları Dönüştürün"
linkTitle: "Convert Archives and Containers"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "ZIP, RAR, 7Z, OST, PST ve diğer kapsayıcı formatlarını açın, içeriklerini dönüştürün ve .NET üzerinden Python için GroupDocs.Conversion ile tek bir Converter.convert() çağrısında birleşik bir çıktı belgesi yazın."
type: docs
url: /tr/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


Bu konu, sıkıştırılmış veya paketlenmiş dosyalar gibi belge kapları içinde gömülü dosyaların nasıl tek tek çıktı dosyalarına dönüştürüleceğini ele alır. Aşağıdaki diyagram, bir belge kabı içinde dosyaların çıkarılması ve dönüştürülmesi sürecini gösterir:

flowchart LR
%% Nodes
A["Belge Kabı"]
B["Çıkarma"]
C["Dönüştürme"]
D["Dönüştürülmüş Dosya 1"]
E["Dönüştürülmüş Dosya 2"]
F["Dönüştürülmüş Dosya N"]

%% Düğümler arasındaki kenar bağlantıları
A --> B --> C --> D
C --> E
C --> F

Çıkarma ve Dönüştürme işlemleri, [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) sınıfının `convert(file_path, convert_options)` yöntemine yapılan tek bir çağrı içinde gerçekleştirilir. GroupDocs.Conversion konteyneri açar, içinde bulunan dosyaları dönüştürür ve birleştirilmiş bir çıktı belgesi yazar.

## Document Container File Types

Aşağıdaki dosya türleri belge konteyneri olarak kabul edilir:

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

Aşağıdaki örnek, bir ZIP arşivinin içeriğini tek bir birleştirilmiş PDF'ye nasıl dönüştüreceğinizi gösterir:

{{< tabs \"example-1\">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Girdi belge konteyneriyle Converter'ı örnekleyin
    with Converter("./compressed.zip") as converter:
        # Dönüştürme seçeneklerini örnekleyin
        pdf_convert_options = PdfConvertOptions()

        # Arşivi çıkarın, içindeki dosyaları dönüştürün ve birleştirilmiş bir PDF olarak kaydedin
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) tıklayın.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
