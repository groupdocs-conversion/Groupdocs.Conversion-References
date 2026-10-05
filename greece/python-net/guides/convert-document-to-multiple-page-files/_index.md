---
title: "Μετατροπή εγγράφου σε αρχεία πολλαπλών σελίδων"
linkTitle: "Convert Document To Multiple"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /el/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Μετατροπή εγγράφου σε αρχεία πολλαπλών σελίδων
linkTitle: Μετατροπή σε Πολλαπλά Αρχεία
weight: 3
description: "Αποδίδεται κάθε σελίδα ενός πολυσέλιδου εγγράφου σε δικό της αρχείο εξόδου — επαναλάβετε το page_number με pages_count=1 και το Converter.convert() για να παραχθεί ένα PNG, PDF ή εικόνα ανά σελίδα με το GroupDocs.Conversion για Python μέσω .NET."
keywords: μετατροπή σε πολλαπλά αρχεία, έξοδος ανά σελίδα, page_number, pages_count, βρόχος σελίδας, μετατροπή σελίδων παρουσίασης, μετατροπή σελίδων PDF σε PNG, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion για Python μέσω .NET
hideChildren: false
toc: true
---

Αυτό το θέμα τεκμηρίωσης καλύπτει τη μετατροπή ενός ενιαίου πολυσέλιδου εγγράφου σε ξεχωριστά αρχεία σελίδων. Το παρακάτω διάγραμμα απεικονίζει τη διαδικασία μετατροπής ενός πολυσέλιδου αρχείου σε ξεχωριστές σελίδες:

flowchart LR
%% Nodes
A["Έγγραφο Εισόδου"]
B["Μετατροπή"]
C["Μετατρεπόμενη Σελίδα 1"]
D["Μετατρεπόμενη Σελίδα 2"]
E["Μετατρεπόμενη Σελίδα N"]

%% Συνδέσεις ακμών μεταξύ κόμβων
A --> B --> C
B --> D
B --> E

Για να μετατρέψετε ένα έγγραφο σε αρχεία ανά σελίδα, χρησιμοποιήστε τη μέθοδο `Converter.convert(file_path, convert_options)` μαζί με τα χαρακτηριστικά `page_number` και `pages_count` στις υποστηριζόμενες κλάσεις [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/).

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

Για να δημιουργήσετε ένα αρχείο εξόδου ανά σελίδα, επαναλάβετε από `1` έως `converter.get_document_info().pages_count`, ενημερώνοντας το `page_number` σε κάθε επανάληψη και γράφοντας σε διαφορετική διαδρομή εξόδου. Ορίζοντας `pages_count = 1` διασφαλίζει ότι κάθε κλήση εκδίδει μία μόνο σελίδα.

## Supported ConvertOptions Classes

Οι παρακάτω κλάσεις [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) εκθέτουν τα χαρακτηριστικά `page_number` και `pages_count` που χρησιμοποιούνται σε αυτό το θέμα:

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

## Example 1: Convert All Pages of a Document and Save Output to a Folder

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε κάθε διαφάνεια σε μια παρουσίαση PPTX σε εικόνα PNG και να αποθηκεύσετε τις εικόνες εξόδου σε έναν καθορισμένο φάκελο.
 
Το πρότυπο ονόματος αρχείου για τα αρχεία εξόδου είναι `converted-page-{page number}.{output file extension}`. Σε αυτό το παράδειγμα, η πρώτη διαφάνεια θα αποθηκευτεί ως `converted-page-1.png`.

{{< tabs "example-1">}}
{{< tab "convert_all_document_pages.py" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Αρχικοποιήστε τον Converter με το έγγραφο εισόδου.
    with Converter("./basic-presentation.pptx") as converter:
        # Καθορίστε τον συνολικό αριθμό σελίδων στο πηγαίο έγγραφο
        pages_count = converter.get_document_info().pages_count

        # Δημιουργήστε τις επιλογές μετατροπής μία φορά και επαναχρησιμοποιήστε τις μέσα στον βρόχο
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Μετατρέψτε κάθε σελίδα σε ξεχωριστό αρχείο PNG
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "convert-all-document-pages-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (26 KB)
converted-pages/converted-page-10.png (81 KB)
converted-pages/converted-page-11.png (67 KB)
converted-pages/converted-page-12.png (70 KB)
converted-pages/converted-page-13.png (36 KB)
converted-pages/converted-page-2.png (34 KB)
converted-pages/converted-page-3.png (797 KB)
converted-pages/converted-page-4.png (1262 KB)
converted-pages/converted-page-5.png (75 KB)
converted-pages/converted-page-6.png (33 KB)
[TRUNCATED] (13 files total)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_all_document_pages/convert-all-document-pages-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Convert a Specific Page and Save Output to a File

Μάθετε πώς να λάβετε τον αριθμό των σελίδων του εγγράφου στο θέμα τεκμηρίωσης [Getting Document Information]().

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε μια συγκεκριμένη διαφάνεια σε μια παρουσίαση PPTX και να την αποθηκεύσετε ως ξεχωριστό αρχείο.

{{< tabs "example-2">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Αρχικοποιήστε τον Converter με το έγγραφο εισόδου.
    with Converter("./basic-presentation.pptx") as converter:
        # Δημιουργήστε τις επιλογές μετατροπής
        png_convert_options = ImageConvertOptions()
        # Ορίστε τη μορφή εξόδου ως PNG
        png_convert_options.format = ImageFileType.PNG

        # Καθορίστε τη μοναδική σελίδα προς μετατροπή
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Αποθηκεύστε τη μετατρεπόμενη σελίδα σε ένα αρχείο
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Μάθετε πώς να λάβετε τον αριθμό των σελίδων του εγγράφου στο θέμα τεκμηρίωσης [Getting Document Information]().

Εάν χρειάζεστε τη μετατρεπόμενη σελίδα ως ενδιάμεση μνήμη (π.χ., για να τη προωθήσετε σε άλλο API χωρίς να αγγίξετε το σύστημα αρχείων μετά), μετατρέψτε πρώτα τη σελίδα σε αρχείο και στη συνέχεια διαβάστε το σε ένα αντικείμενο `BytesIO`:

{{< tabs \"example-3\">}}
{{< tab "convert_specific_document_page_to_stream.py" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # Αρχικοποιήστε τον Converter με το έγγραφο εισόδου.
    with Converter("./basic-presentation.pptx") as converter:
        # Δημιουργήστε τις επιλογές μετατροπής
        png_convert_options = ImageConvertOptions()
        # Ορίστε τη μορφή εξόδου ως PNG
        png_convert_options.format = ImageFileType.PNG

        # Καθορίστε τη μοναδική σελίδα προς μετατροπή
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Μετατρέψτε και αποθηκεύστε τη σελίδα σε αρχείο στο δίσκο
        converter.convert(output_file, png_convert_options)

    # Φορτώστε τη μετατρεπόμενη σελίδα σε ροή μνήμης για περαιτέρω χρήση
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # Το page_stream τώρα περιέχει τα bytes PNG και μπορεί να περαστεί σε οποιονδήποτε καταναλωτή
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
