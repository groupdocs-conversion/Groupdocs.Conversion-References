---
title: "Μετατροπή εγγράφου σε άλλη μορφή"
linkTitle: "Convert to Another Format"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Μετατρέψτε ένα μόνο έγγραφο από μια μορφή σε άλλη, προαιρετικά επιλέγοντας συγκεκριμένες σελίδες ή ένα εύρος σελίδων χρησιμοποιώντας τα χαρακτηριστικά pages / page_number / pages_count στο ConvertOptions με το GroupDocs.Conversion για Python μέσω .NET."
type: docs
url: /el/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Αυτό το θέμα τεκμηρίωσης καλύπτει τη μετατροπή ενός μόνο εγγράφου σε άλλη μορφή, όπου παράγεται μόνο ένα έγγραφο ως έξοδος. Το παρακάτω διάγραμμα απεικονίζει τη διαδικασία μετατροπής ενός αρχείου από μια μορφή σε άλλη:

flowchart LR
%% Nodes
A["Εγγραφή Εισόδου (π.χ. DOCX)"]
B["Μετατροπή"]
C["Μετατρεπόμενο Έγγραφο (π.χ. PDF)"]

%% Συνδέσεις ακμών μεταξύ κόμβων
A --> B --> C

Για να μετατρέψετε και να αποθηκεύσετε ένα έγγραφο, χρησιμοποιήστε τις παρακάτω μεθόδους κλάσης [`Converter`](/conversion/python-net/groupdocs.conversion/converter/):

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

Η παρακάτω λίστα των κλάσεων [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) μπορεί να χρησιμοποιηθεί για τη μετατροπή ενός εγγράφου σε μια συγκεκριμένη μοναδική μορφή εξόδου:

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **EmailConvertOptions** – Options for converting to [Email]() formats (e.g., EML, MSG).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **ProjectManagementConvertOptions** – Options for converting to [Project Management]() formats (e.g., MPP).
- **GisConvertOptions** – Options for converting to [GIS]() formats.
- **FontConvertOptions** – Options for converting to [Font]() formats (e.g., TTF, OTF).
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).
- **CompressionConvertOptions** – Options for converting to [Compression]() formats (e.g., ZIP).
- **NoConvertOptions** – A special option class that instructs the converter to copy the source document without any modifications.

### Example 1: Convert a Document to Another Format

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε ένα αρχείο DOCX σε PDF:

{{< tabs "example-1">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Instantiate Converter with the input document 
    with Converter("./business-plan.docx") as converter:
        # Δημιουργήστε αντικείμενα επιλογών μετατροπής για να ορίσετε τη μορφή εξόδου
        pdf_convert_options = PdfConvertOptions()
        
        # Μετατρέψτε το εισαγόμενο έγγραφο σε PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

Από προεπιλογή, κάθε μία από τις κλάσεις [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) έχει τη δική της προεπιλεγμένη μορφή προορισμού. Για παράδειγμα, η προεπιλεγμένη μορφή εξόδου για το [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) είναι το [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

Για να ορίσετε διαφορετική μορφή εξόδου εντός της οικογένειας μορφών, χρησιμοποιήστε την ιδιότητα `format`. Το παρακάτω παράδειγμα δείχνει πώς να καθορίσετε τη μορφή προορισμού ως `TXT` κατά τη μετατροπή ενός αρχείου `DOCX`:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Instantiate Converter with the input document 
    with Converter("./business-plan.docx") as converter:
        # Δημιουργήστε επιλογές μετατροπής για να ορίσετε τη μορφή εξόδου· προεπιλογή είναι DOCX
        word_convert_options = WordProcessingConvertOptions()
        # Αλλάξτε τη μορφή εξόδου εντός της οικογένειας μορφών από DOCX σε TXT.
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Μετατρέψτε το έγγραφο εισόδου σε TXT.
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"business-plan.txt\" >}}
```text
﻿HOME BASED

PROFESSIONAL SERVICES

Business Plan

[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/specify_output_format/business-plan.txt)
{{< /tab >}}
{{< /tabs >}}

## Specify Document Pages to Convert

Μάθετε πώς να λάβετε τον αριθμό των σελίδων του εγγράφου στο θέμα τεκμηρίωσης [Getting Document Information]().

Για να μετατρέψετε συγκεκριμένες σελίδες εγγράφου, μπορείτε να χρησιμοποιήσετε τις παρακάτω κλάσεις [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/), οι οποίες παρέχουν τα χαρακτηριστικά `pages`, `page_number` και `pages_count`. Αυτές οι επιλογές σας επιτρέπουν να ορίσετε μεμονωμένες σελίδες ή ένα εύρος σελίδων για μετατροπή.

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

### Example 1: Convert Specific Document Pages to Another Format

Μπορείτε να καθορίσετε ποιες σελίδες εγγράφου θέλετε να μετατρέψετε, όπως φαίνεται στο παρακάτω παράδειγμα:

{{< tabs \"example-3\">}}
{{< tab \"convert_specific_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Instantiate Converter with the input document 
    with Converter("./business-plan.docx") as converter:
        # Δημιουργήστε αντικείμενα επιλογών μετατροπής για να ορίσετε τη μορφή εξόδου
        pdf_convert_options = PdfConvertOptions()
        # Καθορίστε ποιες σελίδες εγγράφου θα μετατραπούν
        pdf_convert_options.pages = [1, 3, 5]

        # Μετατρέψτε τις καθορισμένες σελίδες του εισερχόμενου εγγράφου σε PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"pages-1-3-5.pdf\" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

Ως εναλλακτική, μπορείτε να καθορίσετε έναν αριθμό διαδοχικών σελίδων για μετατροπή, όπως φαίνεται στο παρακάτω παράδειγμα:

{{< tabs \"example-4\">}}
{{< tab \"convert_consecutive_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Instantiate Converter with the input document 
    with Converter("./business-plan.docx") as converter:
        # Δημιουργήστε αντικείμενα επιλογών μετατροπής για να ορίσετε τη μορφή εξόδου
        pdf_convert_options = PdfConvertOptions()
        # Καθορίστε τη σελίδα έναρξης και τον αριθμό των σελίδων για μετατροπή
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Μετατρέψτε το καθορισμένο εύρος σελίδων του εγγράφου σε PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"pages-1-through-5.pdf\" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
