---
title: "convert Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument."
type: docs
url: /de/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument.

Mehr erfahren:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable, das einen Stream empfängt und das konvertierte Dokument darin speichert. |
| convert_options | `ConvertOptions` | Konvertierungsoptionen, die für den gewünschten Zieldateityp gelten. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Instanziieren Sie den Converter mit dem Eingabedokument
    with Converter("./business-plan.docx") as converter:
        # Definieren Sie Konvertierungsoptionen für die PDF-Ausgabe
        pdf_options = PdfConvertOptions()
        # Konvertiere das Dokument und speichere es als PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument.

Mehr erfahren:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Die Konvertierungsoptionen, die für den gewünschten Zieldateityp gelten. |
| document_completed | `Action[ConvertedContext]` | Delegate, das den konvertierten Dokumenten-Stream empfängt. Signatur: `Action<ConvertedContext>`. Der Parameter `ConvertedContext` enthält den konvertierten Dokumenten-Stream und Metadaten. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument.

Mehr erfahren:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase], das den Stream zum Speichern des konvertierten Dokuments bereitstellt. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions], das Konvertierungsoptionen bereitstellt. |

**Returns:** None.

### Beispiel

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

Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument.

Mehr erfahren

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] stellt Konvertierungsoptionen bereit. Der Parameter `ConvertContext` enthält Informationen über den Konvertierungsvorgang. |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] empfängt den konvertierten Dokumenten-Stream. Der Parameter `ConvertedContext` enthält den konvertierten Dokumenten-Stream und Metadaten. |

**Returns:** None.

## convert {#file_path-convert_options}

Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument.

Mehr erfahren:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad zum Quelldokument. |
| convert_options | `ConvertOptions` | Die Konvertierungsoptionen, die für den gewünschten Zieldateityp spezifisch sind. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Konvertiert das Quelldokument und speichert das konvertierte Dokument Seite für Seite.

Mehr erfahren

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] das einen Stream zum Speichern jeder konvertierten Seite bereitstellt. Der `SavePageContext`‑Parameter enthält die Seitennummer und Dokumentinformationen. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] das Konvertierungsoptionen bereitstellt. Der `ConvertContext`‑Parameter enthält Informationen über den Konvertierungsvorgang. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Konvertiert das Quelldokument und speichert das konvertierte Dokument Seite für Seite.

Mehr erfahren
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable das einen Stream zum Speichern jeder konvertierten Seite bereitstellt. Signatur: `Func<SavePageContext, Stream>`. Der `SavePageContext`‑Parameter enthält die Seitennummer und Dokumentinformationen. |
| convert_options | `ConvertOptions` | Die Konvertierungsoptionen, die für den gewünschten Zieldateityp spezifisch sind. |

**Returns:** None.

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Konvertiert das Quelldokument und speichert das konvertierte Dokument Seite für Seite.

Mehr erfahren

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Die Konvertierungsoptionen, die für den gewünschten Zieldateityp gelten. |
| document_completed | `Action[ConvertedPageContext]` | Callable das jede konvertierte Seite empfängt. Der `ConvertedPageContext`‑Parameter enthält die Seitennummer, den Stream, den Quelldateinamen und den Zieldateityp. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Konvertiert das Quelldokument und speichert das konvertierte Dokument Seite für Seite.

Mehr erfahren

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Delegate das Konvertierungsoptionen bereitstellt. Der `ConvertContext`‑Parameter enthält Informationen über den Konvertierungsvorgang. |
| document_completed | `Action[ConvertedPageContext]` | Delegate das jede konvertierte Seite empfängt. Der `ConvertedPageContext`‑Parameter enthält die Seitennummer, den Stream, den Quelldateinamen und den Zieldateityp. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Siehe auch
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
