---
title: "μέθοδος convert"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο."
type: docs
url: /el/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

Μάθετε περισσότερα:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Κλήσιμο που λαμβάνει ένα stream και αποθηκεύει το μετατρεπόμενο έγγραφο σε αυτό. |
| convert_options | `ConvertOptions` | Επιλογές μετατροπής ειδικές για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Αρχικοποιήστε τον Converter με το έγγραφο εισόδου.
    with Converter("./business-plan.docx") as converter:
        # Ορίστε τις επιλογές μετατροπής για έξοδο PDF
        pdf_options = PdfConvertOptions()
        # Μετατρέψτε το έγγραφο και αποθηκεύστε το ως PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

Μάθετε περισσότερα:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Οι επιλογές μετατροπής που είναι συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
| document_completed | `Action[ConvertedContext]` | Αντιπρόσωπος που λαμβάνει τη ροή του μετατρεπόμενου εγγράφου. Υπογραφή: `Action<ConvertedContext>`. Η παράμετρος `ConvertedContext` περιέχει τη ροή του μετατρεπόμενου εγγράφου και τα μεταδεδομένα. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

Μάθετε περισσότερα:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase] που παρέχει τη ροή για την αποθήκευση του μετατρεπόμενου εγγράφου. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] που παρέχει επιλογές μετατροπής. |

**Returns:** None.

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert(
            lambda ctx: open("output.pdf", "wb"),
            lambda ctx: PdfConvertOptions(),
            cancellationToken=None
        )
```

## convert {#convert_options_provider-document_completed}

Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

Μάθετε περισσότερα

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] Παρέχει επιλογές μετατροπής. Η παράμετρος `ConvertContext` περιέχει πληροφορίες σχετικά με τη λειτουργία μετατροπής. |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] Λαμβάνει τη ροή του μετατρεπόμενου εγγράφου. Η παράμετρος `ConvertedContext` περιέχει τη ροή του μετατρεπόμενου εγγράφου και τα μεταδεδομένα. |

**Returns:** None.

## convert {#file_path-convert_options}

Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

Μάθετε περισσότερα:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| convert_options | `ConvertOptions` | Οι επιλογές μετατροπής που είναι συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα.

Μάθετε περισσότερα

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] που παρέχει μια ροή για την αποθήκευση κάθε μετατρεπόμενης σελίδας. Η παράμετρος `SavePageContext` περιέχει τον αριθμό σελίδας και πληροφορίες εγγράφου. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] που παρέχει επιλογές μετατροπής. Η παράμετρος `ConvertContext` περιέχει πληροφορίες σχετικά με τη λειτουργία μετατροπής. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα.

Μάθετε περισσότερα
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable που παρέχει μια ροή για την αποθήκευση κάθε μετατρεπόμενης σελίδας. Υπογραφή: `Func<SavePageContext, Stream>`. Η παράμετρος `SavePageContext` περιέχει τον αριθμό σελίδας και πληροφορίες εγγράφου. |
| convert_options | `ConvertOptions` | Οι επιλογές μετατροπής που είναι συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |

**Returns:** None.

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα.

Μάθετε περισσότερα

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Οι επιλογές μετατροπής που είναι συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
| document_completed | `Action[ConvertedPageContext]` | Callable που λαμβάνει κάθε μετατρεπόμενη σελίδα. Η παράμετρος `ConvertedPageContext` περιέχει τον αριθμό σελίδας, τη ροή, το όνομα του πηγαίου αρχείου και τον τύπο αρχείου προορισμού. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Μετατρέπει το πηγαίο έγγραφο και αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα.

Μάθετε περισσότερα

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Αντιπρόσωπος που παρέχει επιλογές μετατροπής. Η παράμετρος `ConvertContext` περιέχει πληροφορίες σχετικά με τη λειτουργία μετατροπής. |
| document_completed | `Action[ConvertedPageContext]` | Αντιπρόσωπος που λαμβάνει κάθε μετατρεπόμενη σελίδα. Η παράμετρος `ConvertedPageContext` περιέχει τον αριθμό σελίδας, τη ροή, το όνομα του πηγαίου αρχείου και τον τύπο αρχείου προορισμού. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Δείτε επίσης
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
