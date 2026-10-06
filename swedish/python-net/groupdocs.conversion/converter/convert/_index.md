---
title: "convert‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Konverterar källdokumentet och sparar hela det konverterade dokumentet."
type: docs
url: /sv/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Konverterar källdokumentet och sparar hela det konverterade dokumentet.

Läs mer:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Anropbar funktion som tar emot en ström och sparar det konverterade dokumentet till den. |
| convert_options | `ConvertOptions` | Konverteringsalternativ specifika för den önskade målfiltypen. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Instansiera Converter med inmatningsdokumentet
    with Converter("./business-plan.docx") as converter:
        # Definiera konverteringsalternativ för PDF-utdata
        pdf_options = PdfConvertOptions()
        # Konvertera dokumentet och spara som PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Konverterar källdokumentet och sparar hela det konverterade dokumentet.

Läs mer:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options | `ConvertOptions` | De konverteringsalternativen som är specifika för önskad målfiltyp. |
| document_completed | `Action[ConvertedContext]` | Delegat som tar emot den konverterade dokumentströmmen. Signatur: `Action<ConvertedContext>`. Parametern `ConvertedContext` innehåller den konverterade dokumentströmmen och metadata. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Konverterar källdokumentet och sparar hela det konverterade dokumentet.

Läs mer:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase] som tillhandahåller strömmen för att spara det konverterade dokumentet. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] som tillhandahåller konverteringsalternativ. |

**Returns:** None.

### Exempel

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

Konverterar källdokumentet och sparar hela det konverterade dokumentet.

Läs mer

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] Tillhandahåller konverteringsalternativ. Parametern `ConvertContext` innehåller information om konverteringsoperationen. |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] Tar emot den konverterade dokumentströmmen. Parametern `ConvertedContext` innehåller den konverterade dokumentströmmen och metadata. |

**Returns:** None.

## convert {#file_path-convert_options}

Konverterar källdokumentet och sparar hela det konverterade dokumentet.

Läs mer:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen till källdokumentet. |
| convert_options | `ConvertOptions` | Konverteringsalternativen som är specifika för den önskade målfiltypen. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Konverterar källdokumentet och sparar det konverterade dokumentet sida för sida.

Läs mer

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] som tillhandahåller en ström för att spara varje konverterad sida. Parametern `SavePageContext` innehåller sidnummer och dokumentinformation. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] som tillhandahåller konverteringsalternativ. Parametern `ConvertContext` innehåller information om konverteringsoperationen. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Konverterar källdokumentet och sparar det konverterade dokumentet sida för sida.

Läs mer
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable som tillhandahåller en ström för att spara varje konverterad sida. Signatur: `Func<SavePageContext, Stream>`. Parametern `SavePageContext` innehåller sidnummer och dokumentinformation. |
| convert_options | `ConvertOptions` | Konverteringsalternativen som är specifika för den önskade målfiltypen. |

**Returns:** None.

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Konverterar källdokumentet och sparar det konverterade dokumentet sida för sida.

Läs mer

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options | `ConvertOptions` | De konverteringsalternativen som är specifika för önskad målfiltyp. |
| document_completed | `Action[ConvertedPageContext]` | Callable som tar emot varje konverterad sida. Parametern `ConvertedPageContext` innehåller sidnummer, ström, källfilnamn och målfiltyp. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Konverterar källdokumentet och sparar det konverterade dokumentet sida för sida.

Läs mer

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Delegat som tillhandahåller konverteringsalternativ. Parametern `ConvertContext` innehåller information om konverteringsoperationen. |
| document_completed | `Action[ConvertedPageContext]` | Delegat som tar emot varje konverterad sida. Parametern `ConvertedPageContext` innehåller sidnummer, ström, källfilnamn och målfiltyp. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Se även
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
