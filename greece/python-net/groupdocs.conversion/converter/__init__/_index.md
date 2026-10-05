---
title: "κατασκευαστής __init__"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του Converter."
type: docs
url: /el/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Αρχικοποιεί μια νέα παρουσία του Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Η μέθοδος που επιστρέφει μια αναγνώσιμη ροή. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `source_stream_provider` είναι None. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Αρχικοποιεί μια νέα [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) αντικείμενο.

Μάθετε περισσότερα

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Η μέθοδος που επιστρέφει μια αναγνώσιμη ροή. |
| settings | `Func[ConverterSettings]` | Οι ρυθμίσεις του Converter. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Αρχικοποιεί μια νέα [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) αντικείμενο.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable που επιστρέφει ένα αναγνώσιμο ρεύμα `io.RawIOBase`. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] που παρέχει επιλογές φόρτωσης για το έγγραφο. Η παράμετρος `LoadContext` περιέχει πληροφορίες σχετικά με το έγγραφο που φορτώνεται. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` που καθορίζει τις ρυθμίσεις του μετατροπέα. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Αρχικοποιεί ένα νέο Converter με ρητές εκδηλώσεις μετατροπής.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable που επιστρέφει ένα αναγνώσιμο ρεύμα. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable που παρέχει επιλογές φόρτωσης για το έγγραφο. |
| settings | `Func[ConverterSettings]` | Ρυθμίσεις Converter. |
| events | `Func[ConversionEvents]` | Callable που παρέχει συγκεντρωμένα `ConversionEvents` που έχουν καταχωρηθεί για τη διάρκεια ζωής του μετατροπέα. |

## __init__ {#source_stream_provider-settings-events}

Αρχικοποιεί μια νέα παρουσία του Converter με ρητές εκδηλώσεις μετατροπής.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable που επιστρέφει ένα αναγνώσιμο ρεύμα. |
| settings | `Func[ConverterSettings]` | Ρυθμίσεις Converter. |
| events | `Func[ConversionEvents]` | Delegate που παρέχει συγκεντρωμένα `ConversionEvents` που έχουν καταχωρηθεί για τη διάρκεια ζωής του μετατροπέα. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Αρχικοποιεί μια νέα παρουσία του Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Αρχικοποιεί μια νέα [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) αντικείμενο.

Μάθετε περισσότερα

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| settings | `Func[ConverterSettings]` | Οι ρυθμίσεις του Converter. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Μάθετε περισσότερα

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate που παρέχει επιλογές φόρτωσης για το έγγραφο. Υπογραφή: `Func<LoadContext, LoadOptions>`. Η παράμετρος `LoadContext` περιέχει πληροφορίες σχετικά με το έγγραφο που φορτώνεται. |
| settings | `Func[ConverterSettings]` | Οι ρυθμίσεις του Converter. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Αρχικοποιεί ένα νέο Converter με ρητές εκδηλώσεις μετατροπής.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate που παρέχει επιλογές φόρτωσης για το έγγραφο. |
| settings | `Func[ConverterSettings]` | Οι ρυθμίσεις του Converter. |
| events | `Func[ConversionEvents]` | Delegate που παρέχει συγκεντρωμένα `ConversionEvents` που έχουν καταχωρηθεί για τη διάρκεια ζωής του μετατροπέα. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Αρχικοποιεί ένα νέο Converter με ρητές εκδηλώσεις μετατροπής.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| settings | `Func[ConverterSettings]` | Οι ρυθμίσεις του Converter. |
| events | `Func[ConversionEvents]` | Delegate που παρέχει συγκεντρωμένα ConversionEvents που έχουν καταχωρηθεί για τη διάρκεια ζωής του μετατροπέα. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Δείτε επίσης
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
