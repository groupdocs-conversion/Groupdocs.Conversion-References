---
title: "Load File From Local Disk"
linkTitle: "Load From Local Disk"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Instantiate the Converter class with an absolute or relative file path to convert a document stored on the local filesystem with GroupDocs.Conversion for Python via .NET."
type: docs
url: /el/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


To load a source file from your local disk, you can use the [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class constructor in GroupDocs.Conversion. The API offers several overloads, allowing flexibility for various settings and options:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Each constructor requires the `filePath` parameter, which defines the path to the source file. You can specify this as an absolute or relative path. Note that if the specified file path does not exist, an exception will be raised.

GroupDocs.Conversion will access the file only when an action (e.g., conversion) is performed using the [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class instance.

The following Python example demonstrates loading a file from a local disk and converting it to PDF:

{{< tabs "code-example">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Specify source file location
    converter = Converter("./business-plan.docx")
    
    # Specify output file location and convert options
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Convert and save to output path
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Το GroupDocs.Conversion καθορίζει τον τύπο του αρχείου με βάση την επέκτασή του. Εάν η επέκταση του αρχείου δεν έχει οριστεί, το GroupDocs.Conversion θα προσπαθήσει να εντοπίσει αυτόματα τον τύπο του αρχείου. Ανάλογα με τον τύπο και το μέγεθος του αρχείου, η αυτόματη ανίχνευση τύπου αρχείου καταναλώνει πρόσθετους πόρους, όπως μνήμη και χρόνο CPU. Συνεπώς, συνιστούμε να διασφαλίζετε ότι ένα αρχείο έχει τη σωστή επέκταση ή να χρησιμοποιείτε τον κατασκευαστή της κλάσης Converter που δέχεται επιλογές φόρτωσης.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Ανατρέξτε στην [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) για περισσότερες λεπτομέρειες σχετικά με τη χρήση επιλογών φόρτωσης και άλλων υπερφορτώσεων κατασκευαστών.
