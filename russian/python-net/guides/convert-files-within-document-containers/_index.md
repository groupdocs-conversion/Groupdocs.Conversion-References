---
title: "Преобразование файлов внутри контейнеров документов"
linkTitle: "Convert Archives and Containers"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Откройте форматы контейнеров ZIP, RAR, 7Z, OST, PST и другие, преобразуйте их содержимое и запишите объединённый выходной документ одним вызовом Converter.convert() с помощью GroupDocs.Conversion для Python через .NET."
type: docs
url: /ru/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


В этой теме рассматривается, как преобразовать файлы, встроенные в контейнеры документов, такие как сжатые или упакованные файлы, в отдельные выходные файлы. На следующей диаграмме показан процесс извлечения и преобразования файлов внутри контейнера документов:

flowchart LR
%% Nodes
A[\"Контейнер документа\"]
B[\"Извлечение\"]
C[\"Преобразование\"]
D[\"Преобразованный файл 1\"]
E[\"Преобразованный файл 2\"]
F[\"Преобразованный файл N\"]

%% Edge connections between nodes
A --> B --> C --> D
C --> E
C --> F

Процессы извлечения и конвертации выполняются в рамках одного вызова метода `convert(file_path, convert_options)` класса [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). GroupDocs.Conversion открывает контейнер, конвертирует содержащиеся в нём файлы и записывает объединённый выходной документ.

## Document Container File Types

Следующие типы файлов считаются документными контейнерами:

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

В следующем примере показано, как конвертировать содержимое ZIP‑архива в один объединённый PDF:

{{< tabs \"example-1\">}}
{{< tab \"convert_files_within_document_container.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Создайте экземпляр Converter с входным документным контейнером
    with Converter("./compressed.zip") as converter:
        # Создайте экземпляр параметров конвертации
        pdf_convert_options = PdfConvertOptions()

        # Извлеките архив, конвертируйте содержащиеся файлы и сохраните объединённый PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab \"compressed.zip\" >}}

`compressed.zip` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip), чтобы скачать его.

{{< /tab >}}
{{< tab \"converted.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
