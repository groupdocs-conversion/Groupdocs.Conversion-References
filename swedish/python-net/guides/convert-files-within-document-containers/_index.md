---
title: "Konvertera filer i dokumentbehållare"
linkTitle: "Convert Archives and Containers"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Öppna ZIP-, RAR-, 7Z-, OST-, PST- och andra behållarformat, konvertera deras innehåll och skriv ett konsoliderat utdata‑dokument i ett enda Converter.convert()-anrop med GroupDocs.Conversion för Python via .NET."
type: docs
url: /sv/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


Detta ämne täcker hur man konverterar filer som är inbäddade i dokumentbehållare, såsom komprimerade eller paketerade filer, till individuella utdatafiler. Följande diagram illustrerar processen för att extrahera och konvertera filer inom en dokumentbehållare:

flowchart LR
%% Nodes
A["Dokumentbehållare"]
B["Extraktion"]
C["Konvertering"]
D["Konverterad fil 1"]
E["Konverterad fil 2"]
F["Konverterad fil N"]

%% Kantanslutningar mellan noder
A --> B --> C --> D
C --> E
C --> F

Extraktions- och konverteringsprocesserna utförs inom ett enda anrop till `convert(file_path, convert_options)`‑metoden i [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑klassen. GroupDocs.Conversion öppnar behållaren, konverterar filerna den innehåller och skriver ett konsoliderat utdata‑dokument.

## Document Container File Types

Följande filtyper betraktas som dokumentbehållare:

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

Följande exempel visar hur man konverterar innehållet i ett ZIP‑arkiv till en enda sammanslagen PDF:

{{< tabs "example-1">}}
{{< tab \"convert_files_within_document_container.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Instansiera Converter med inmatningsdokumentbehållaren
    with Converter("./compressed.zip") as converter:
        # Instansiera konverteringsalternativ
        pdf_convert_options = PdfConvertOptions()

        # Extrahera arkivet, konvertera de innehållande filerna och spara en sammanslagen PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab \"compressed.zip\" >}}

`compressed.zip` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) för att ladda ner den.

{{< /tab >}}
{{< tab \"converted.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
