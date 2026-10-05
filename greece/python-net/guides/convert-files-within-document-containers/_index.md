---
title: "Μετατροπή αρχείων εντός δοχείων εγγράφων"
linkTitle: "Convert Archives and Containers"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ανοίξτε αρχεία ZIP, RAR, 7Z, OST, PST και άλλες μορφές δοχείων, μετατρέψτε τα περιεχόμενά τους και δημιουργήστε ένα ενοποιημένο έγγραφο εξόδου με μία κλήση Converter.convert() χρησιμοποιώντας το GroupDocs.Conversion για Python μέσω .NET."
type: docs
url: /el/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


Αυτό το θέμα καλύπτει πώς να μετατρέψετε αρχεία ενσωματωμένα σε δοχεία εγγράφων, όπως συμπιεσμένα ή πακεταρισμένα αρχεία, σε μεμονωμένα αρχεία εξόδου. Το παρακάτω διάγραμμα απεικονίζει τη διαδικασία εξαγωγής και μετατροπής αρχείων εντός ενός δοχείου εγγράφου:

flowchart LR
%% Nodes
A[\"Δοχείο Εγγράφου\"]
B[\"Εξαγωγή\"]
C[\"Μετατροπή\"]
D[\"Μετατρεπόμενο Αρχείο 1\"]
E[\"Μετατρεπόμενο Αρχείο 2\"]
F[\"Μετατρεπόμενο Αρχείο N\"]

%% Συνδέσεις ακμών μεταξύ κόμβων
A --> B --> C --> D
C --> E
C --> F

Οι διαδικασίες Εξαγωγής και Μετατροπής εκτελούνται μέσα σε μία κλήση της μεθόδου `convert(file_path, convert_options)` της κλάσης [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). Το GroupDocs.Conversion ανοίγει το container, μετατρέπει τα αρχεία που περιέχει και γράφει ένα ενοποιημένο έγγραφο εξόδου.

## Document Container File Types

Οι παρακάτω τύποι αρχείων θεωρούνται containers εγγράφων:

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

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε τα περιεχόμενα ενός αρχείου ZIP σε ένα ενιαίο PDF:

{{< tabs "example-1">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Δημιουργήστε το Converter με το container εισόδου εγγράφου
    with Converter("./compressed.zip") as converter:
        # Δημιουργήστε τις επιλογές μετατροπής
        pdf_convert_options = PdfConvertOptions()

        # Εξάγετε το αρχείο, μετατρέψτε τα περιεχόμενα αρχεία και αποθηκεύστε ένα ενοποιημένο PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
