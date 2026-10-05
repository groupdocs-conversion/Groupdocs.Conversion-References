---
title: "Οδηγός Γρήγορης Εκκίνησης"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ρυθμίστε ένα εικονικό περιβάλλον, εγκαταστήστε το groupdocs-conversion-net και εκτελέστε τρία ελάχιστα παραδείγματα — DOCX → PDF, PDF → PNG ανά σελίδα, και ZIP → ενοποιημένο PDF — σε λιγότερο από πέντε λεπτά."
type: docs
url: /el/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Αυτός ο οδηγός παρέχει μια γρήγορη επισκόπηση του πώς να ρυθμίσετε και να αρχίσετε να χρησιμοποιείτε το GroupDocs.Conversion for Python μέσω .NET. Αυτή η βιβλιοθήκη επιτρέπει στους προγραμματιστές να μετατρέπουν μεταξύ διαφόρων μορφών αρχείων (π.χ., DOCX, PDF, PNG) με ελάχιστη διαμόρφωση.

## Prerequisites

Για να προχωρήσετε, βεβαιωθείτε ότι έχετε:

1. **Configured** περιβάλλον όπως περιγράφεται στο θέμα [System Requirements]().
2. **Προαιρετικά** μπορείτε να [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) για να δοκιμάσετε όλες τις λειτουργίες του προϊόντος.

## Set Up Your Development Environment

Για βέλτιστες πρακτικές, χρησιμοποιήστε ένα εικονικό περιβάλλον για τη διαχείριση εξαρτήσεων σε εφαρμογές Python. Μάθετε περισσότερα για το εικονικό περιβάλλον στο θέμα τεκμηρίωσης [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Δημιουργήστε ένα εικονικό περιβάλλον:

{{< tabs "example1">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Ενεργοποιήστε ένα εικονικό περιβάλλον:

{{< tabs "example2">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-conversion-net` Package

Αφού ενεργοποιήσετε το εικονικό περιβάλλον, εκτελέστε την παρακάτω εντολή στο τερματικό σας για να εγκαταστήσετε την πιο πρόσφατη έκδοση του πακέτου:

{{< tabs "example3">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

Βεβαιωθείτε ότι το πακέτο εγκαταστάθηκε επιτυχώς. Θα πρέπει να δείτε το μήνυμα

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

Για γρήγορη δοκιμή της βιβλιοθήκης, ας μετατρέψουμε ένα αρχείο DOCX σε PDF. Μπορείτε επίσης να κατεβάσετε την εφαρμογή που θα δημιουργήσουμε [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip).

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Λάβετε την απόλυτη διαδρομή του αρχείου άδειας
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Δημιουργήστε την άδεια και ορίστε τη διαδρομή
        license = License()
        license.set_license(license_path)

    # Φορτώστε το αρχείο DOCX
    with Converter("./business-plan.docx") as converter:
        # Δημιουργήστε επιλογές μετατροπής
        pdf_convert_options = PdfConvertOptions()

        # Μετατρέψτε το DOCX σε PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Η δομή φακέλων σας πρέπει να μοιάζει με την παρακάτω δομή καταλόγου:

```Directory
📂 demo-app
 ├──convert_docx_to_pdf.py
 ├──business-plan.docx
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

Μετά την εκτέλεση της εφαρμογής, μπορείτε να απενεργοποιήσετε το εικονικό περιβάλλον εκτελώντας `deactivate` ή κλείνοντας το τερματικό σας.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

Σε αυτό το παράδειγμα θα μετατρέψουμε τις σελίδες εγγράφου PDF σε PNG. Μπορείτε να κατεβάσετε την εφαρμογή που θα δημιουργήσουμε [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip).

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Λάβετε την απόλυτη διαδρομή του αρχείου άδειας
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Δημιουργήστε την άδεια και ορίστε τη διαδρομή
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Φορτώστε το έγγραφο PDF
    with Converter("./annual-review.pdf") as converter:
        # Καθορίστε τον συνολικό αριθμό σελίδων στο πηγαίο έγγραφο
        pages_count = converter.get_document_info().pages_count

        # Δημιουργήστε επιλογές μετατροπής και επαναχρησιμοποιήστε τις μέσα στον βρόχο
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Μετατρέψτε κάθε σελίδα σε ξεχωριστό αρχείο PNG
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "convert-pdf-pages-to-png-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (1148 KB)
converted-pages/converted-page-2.png (89 KB)
converted-pages/converted-page-3.png (83 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_pdf_pages_to_png/convert-pdf-pages-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Η δομή φακέλων σας πρέπει να μοιάζει με την παρακάτω δομή καταλόγου:

```Directory
📂 demo-app
 ├──annual-review.pdf
 ├──convert_pdf_pages_to_png.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_pdf_pages_to_png">}}
{{< tab "Windows" >}}
```ps
py convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

Μετά την εκτέλεση της εφαρμογής, μπορείτε να απενεργοποιήσετε το εικονικό περιβάλλον εκτελώντας `deactivate` ή κλείνοντας το τερματικό σας.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

Σε αυτό το παράδειγμα θα μετατρέψουμε τα περιεχόμενα ενός αρχείου ZIP σε PDF. Το GroupDocs.Conversion ανοίγει το αρχείο, μετατρέπει τα αρχεία μέσα σε αυτό και δημιουργεί ένα ενιαίο ενοποιημένο PDF που περιέχει κάθε μετατρεπόμενο έγγραφο. Μπορείτε να κατεβάσετε την εφαρμογή που θα δημιουργήσουμε [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip).

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Λάβετε την απόλυτη διαδρομή του αρχείου άδειας
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Δημιουργήστε την άδεια και ορίστε τη διαδρομή
        license = License()
        license.set_license(license_path)

    # Φορτώστε το αρχείο ZIP
    with Converter("./compressed.zip") as converter:
        # Δημιουργήστε επιλογές μετατροπής
        pdf_convert_options = PdfConvertOptions()

        # Αποσυμπιέστε το αρχείο, μετατρέψτε το περιεχόμενό του και αποθηκεύστε ένα ενοποιημένο PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

Η δομή φακέλων σας πρέπει να μοιάζει με την παρακάτω δομή καταλόγου:

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_files_in_archive">}}
{{< tab "Windows" >}}
```ps
py convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< /tabs >}}

Μετά την εκτέλεση της εφαρμογής, μπορείτε να απενεργοποιήσετε το εικονικό περιβάλλον εκτελώντας `deactivate` ή κλείνοντας το τερματικό σας.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

Αφού ολοκληρώσετε τα βασικά, εξερευνήστε πρόσθετους πόρους για να βελτιώσετε τη χρήση σας:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
