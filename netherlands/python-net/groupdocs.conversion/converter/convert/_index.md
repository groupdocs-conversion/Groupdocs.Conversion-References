---
title: "convert-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Converteert het brondocument en slaat het volledige geconverteerde document op."
type: docs
url: /nl/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Converteert het brondocument en slaat het volledige geconverteerde document op.

Meer informatie:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable die een stream ontvangt en het geconverteerde document erin opslaat. |
| convert_options | `ConvertOptions` | Conversie‑opties specifiek voor het gewenste doelbestandstype. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Instantieer Converter met het invoerdocument
    with Converter("./business-plan.docx") as converter:
        # Definieer conversie‑opties voor PDF-uitvoer
        pdf_options = PdfConvertOptions()
        # Converteer het document en sla op als PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Converteert het brondocument en slaat het gehele geconverteerde document op.

Meer informatie:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| convert_options | `ConvertOptions` | De conversie-opties specifiek voor het gewenste doelbestandstype. |
| document_completed | `Action[ConvertedContext]` | Delegate die de geconverteerde documentstroom ontvangt. Handtekening: `Action<ConvertedContext>`. De `ConvertedContext`-parameter bevat de geconverteerde documentstroom en metadata. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Converteert het brondocument en slaat het gehele geconverteerde document op.

Meer informatie:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase] die de stroom levert om het geconverteerde document op te slaan. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] die conversie-opties levert. |

**Returns:** None.

### Voorbeeld

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

Converteert het brondocument en slaat het gehele geconverteerde document op.

Meer informatie

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] Levert conversie-opties. De `ConvertContext`-parameter bevat informatie over de conversie-operatie. |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext>, None] Ontvangt de geconverteerde documentstroom. De `ConvertedContext`-parameter bevat de geconverteerde documentstroom en metadata. |

**Returns:** None.

## convert {#file_path-convert_options}

Converteert het brondocument en slaat het gehele geconverteerde document op.

Meer informatie:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad naar het brondocument. |
| convert_options | `ConvertOptions` | De conversie-opties specifiek voor het gewenste doelbestandstype. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Converteert het brondocument en slaat het geconverteerde document pagina voor pagina op.

Meer informatie

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] die een stroom levert om elke geconverteerde pagina op te slaan. De `SavePageContext`-parameter bevat paginanummer en documentinformatie. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] die conversie-opties levert. De `ConvertContext`-parameter bevat informatie over de conversie-operatie. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Converteert het brondocument en slaat het geconverteerde document pagina voor pagina op.

Meer informatie
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable die een stroom levert om elke geconverteerde pagina op te slaan. Handtekening: `Func<SavePageContext, Stream>`. De `SavePageContext`-parameter bevat paginanummer en documentinformatie. |
| convert_options | `ConvertOptions` | De conversie-opties specifiek voor het gewenste doelbestandstype. |

**Returns:** None.

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Converteert het brondocument en slaat het geconverteerde document pagina voor pagina op.

Meer informatie

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| convert_options | `ConvertOptions` | De conversie-opties specifiek voor het gewenste doelbestandstype. |
| document_completed | `Action[ConvertedPageContext]` | Callable die elke geconverteerde pagina ontvangt. De `ConvertedPageContext`-parameter bevat paginanummer, stroom, bronbestandsnaam en doelbestandstype. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Converteert het brondocument en slaat het geconverteerde document pagina voor pagina op.

Meer informatie

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Delegate die conversie-opties levert. De `ConvertContext`-parameter bevat informatie over de conversie-operatie. |
| document_completed | `Action[ConvertedPageContext]` | Delegate die elke geconverteerde pagina ontvangt. De `ConvertedPageContext`-parameter bevat paginanummer, stroom, bronbestandsnaam en doelbestandstype. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Zie ook
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
