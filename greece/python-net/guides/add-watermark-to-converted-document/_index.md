---
title: "Προσθήκη υδατογραφήματος σε μετατρεπόμενο έγγραφο"
linkTitle: "Add a Watermark"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Επισημάνετε ένα κείμενο υδατογραφήματος σε κάθε σελίδα ενός μετατρεπόμενου εγγράφου με το GroupDocs.Conversion για Python μέσω .NET — ελέγξτε το χρώμα, το μέγεθος, τη θέση, την περιστροφή, τη διαφάνεια και την τοποθέτηση στο προσκήνιο ή στο παρασκήνιο μέσω WatermarkTextOptions."
type: docs
url: /el/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


Αυτό το θέμα εξηγεί πώς να προσθέσετε ένα υδατογράφημα κατά τη διαδικασία μετατροπής χρησιμοποιώντας το GroupDocs.Conversion για Python μέσω .NET. Το υδατογράφημα μπορεί να εφαρμοστεί σε ένα έγγραφο καθώς μετατρέπεται σε άλλη μορφή, βοηθώντας στην προστασία του περιεχομένου και εξασφαλίζοντας ότι είναι αναγνωρίσιμο.

Για να ενεργοποιήσετε την προσθήκη υδατογραφήματος, μπορείτε να χρησιμοποιήσετε το χαρακτηριστικό `watermark` στις κατάλληλες κλάσεις [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Παρακάτω είναι οι υποστηριζόμενες κλάσεις [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) που σας επιτρέπουν να διαμορφώσετε το υδατογράφημα κατά τη μετατροπή:

Αναζητάτε προηγμένες δυνατότητες υδατογραφήματος; Ενώ το GroupDocs.Conversion προσφέρει βασικό υδατογράφημα, μπορείτε να εξερευνήσετε το [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) για μια ολοκληρωμένη λύση με βελτιωμένα χαρακτηριστικά.

## Supported ConvertOptions Classes

Οι παρακάτω κλάσεις [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) που παρέχουν το χαρακτηριστικό `watermark`.

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).

## WatermarkTextOptions Class Attributes

The **`WatermarkTextOptions`** class is used to configure the appearance of the watermark. The following options can be configured for adding a watermark:

- **text**: The text to be used for the watermark.
- **font**: The font name used for the watermark text.
- **color**: The color of the watermark text.
- **width**: The width of the watermark.
- **height**: The height of the watermark.
- **top**: The top position of the watermark.
- **left**: The left position of the watermark.
- **rotation_angle**: The rotation angle of the watermark.
- **transparency**: The transparency level of the watermark.
- **background**: Specifies whether the watermark is stamped as a background. If set to `True`, the watermark is placed at the bottom. By default, it is `False`, and the watermark is placed on top of the content.

## Example: Add a Watermark to Converted Document

The following example demonstrates how to convert DOCX document to PDF and add a watermark:

{{< tabs "example-1">}}
{{< tab "add_watermark_to_converted_document.py" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Instantiate Converter with the input document 
    with Converter("./professional-services.docx") as converter:
        # Set up the watermark options
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Set up the conversion options
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Perform the conversion
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab "professional-services.docx" >}}

`professional-services.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) to download it.

{{< /tab >}}
{{< tab "professional-services.pdf" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
