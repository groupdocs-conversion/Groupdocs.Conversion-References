---
title: "Dateien innerhalb von Dokumentcontainern konvertieren"
linkTitle: "Convert Archives and Containers"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Öffnen Sie ZIP-, RAR-, 7Z-, OST-, PST- und andere Containerformate, konvertieren Sie deren Inhalte und schreiben Sie ein konsolidiertes Ausgabedokument in einem einzigen Converter.convert()‑Aufruf mit GroupDocs.Conversion für Python via .NET."
type: docs
url: /de/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


Dieses Thema behandelt, wie Dateien, die in Dokumentcontainern eingebettet sind, wie komprimierte oder gepackte Dateien, in einzelne Ausgabedateien konvertiert werden. Das folgende Diagramm veranschaulicht den Vorgang des Extrahierens und Konvertierens von Dateien innerhalb eines Dokumentcontainers:

flowchart LR
%% Nodes
A["Dokumentencontainer"]
B["Extraktion"]
C["Konvertierung"]
D["Konvertierte Datei 1"]
E["Konvertierte Datei 2"]
F["Konvertierte Datei N"]

%% Edge connections between nodes
A --> B --> C --> D
C --> E
C --> F

Der Extraktions- und Konvertierungsprozess wird innerhalb eines einzigen Aufrufs der `convert(file_path, convert_options)`‑Methode der [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑Klasse durchgeführt. GroupDocs.Conversion öffnet den Container, konvertiert die darin enthaltenen Dateien und schreibt ein konsolidiertes Ausgabedokument.

## Document Container File Types

Die folgenden Dateitypen werden als Dokumentcontainer betrachtet:

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

Das folgende Beispiel zeigt, wie man den Inhalt eines ZIP‑Archivs in ein einzelnes konsolidiertes PDF konvertiert:

{{< tabs "example-1">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Instanziieren Sie Converter mit dem Eingabedokumentcontainer
    with Converter("./compressed.zip") as converter:
        # Instanziieren Sie Konvertierungsoptionen
        pdf_convert_options = PdfConvertOptions()

        # Extrahieren Sie das Archiv, konvertieren Sie die enthaltenen Dateien und speichern Sie ein konsolidiertes PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) zum Herunterladen.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
