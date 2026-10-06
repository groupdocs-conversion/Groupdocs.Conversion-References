---
title: "Bestanden binnen documentcontainers converteren"
linkTitle: "Convert Archives and Containers"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Open ZIP-, RAR-, 7Z-, OST-, PST- en andere containerformaten, converteer hun inhoud, en schrijf een geconsolideerd uitvoerdocument in één enkele Converter.convert()-aanroep met GroupDocs.Conversion voor Python via .NET."
type: docs
url: /nl/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


Dit onderwerp behandelt hoe bestanden die zijn ingebed in documentcontainers, zoals gecomprimeerde of verpakte bestanden, kunnen worden geconverteerd naar afzonderlijke uitvoerbestanden. Het volgende diagram illustreert het proces van het extraheren en converteren van bestanden binnen een documentcontainer:

flowchart LR
%% Nodes
A["Documentcontainer"]
B["Extractie"]
C["Conversie"]
D["Geconverteerd bestand 1"]
E["Geconverteerd bestand 2"]
F["Geconverteerd bestand N"]

%% Edge connections between nodes
A --> B --> C --> D
C --> E
C --> F

De extractie- en conversieprocessen worden uitgevoerd binnen één enkele aanroep van de `convert(file_path, convert_options)`‑methode van de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑klasse. GroupDocs.Conversion opent de container, converteert de bestanden die het bevat, en schrijft een geconsolideerd output‑document.

## Document Container File Types

De volgende bestandstypen worden beschouwd als documentcontainers:

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

Het volgende voorbeeld laat zien hoe de inhoud van een ZIP‑archief kan worden geconverteerd naar één geconsolideerde PDF:

{{< tabs \"example-1\">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Instantieer Converter met de invoer‑documentcontainer
    with Converter("./compressed.zip") as converter:
        # Instantieer converteeropties
        pdf_convert_options = PdfConvertOptions()

        # Extraheer het archief, converteer de daarin aanwezige bestanden, en sla een geconsolideerde PDF op
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) om het te downloaden.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
