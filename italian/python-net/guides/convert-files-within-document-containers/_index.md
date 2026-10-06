---
title: "Converti file all'interno di contenitori di documento"
linkTitle: "Convert Archives and Containers"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Apri formati di contenitori ZIP, RAR, 7Z, OST, PST e altri, converti il loro contenuto e scrivi un documento di output consolidato in una singola chiamata Converter.convert() con GroupDocs.Conversion per Python tramite .NET."
type: docs
url: /it/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


Questo argomento tratta come convertire file incorporati all'interno di contenitori di documento, come file compressi o impacchettati, in file di output individuali. Il diagramma seguente illustra il processo di estrazione e conversione dei file all'interno di un contenitore di documento:

flowchart LR
%% Nodes
A["Contenitore di documento"]
B["Estrazione"]
C["Conversione"]
D["File convertito 1"]
E["File convertito 2"]
F["File convertito N"]

%% Edge connections between nodes
A --> B --> C --> D
C --> E
C --> F

I processi di estrazione e conversione vengono eseguiti con una singola chiamata al metodo `convert(file_path, convert_options)` della classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). GroupDocs.Conversion apre il contenitore, converte i file al suo interno e scrive un documento di output consolidato.

## Document Container File Types

I seguenti tipi di file sono considerati contenitori di documenti:

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

Il seguente esempio dimostra come convertire il contenuto di un archivio ZIP in un unico PDF consolidato:

{{< tabs \"example-1\">}}
{{< tab \"convert_files_within_document_container.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Istanziare Converter con il contenitore di documento di input
    with Converter("./compressed.zip") as converter:
        # Istanziare le opzioni di conversione
        pdf_convert_options = PdfConvertOptions()

        # Estrai l'archivio, converti i file contenuti e salva un PDF consolidato
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab \"compressed.zip\" >}}

`compressed.zip` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) per scaricarlo.

{{< /tab >}}
{{< tab \"converted.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
