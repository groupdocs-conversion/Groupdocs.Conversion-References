---
title: "__init__-constructor"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van Converter."
type: docs
url: /nl/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Initialiseert een nieuw exemplaar van Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | De methode die een leesbare stroom retourneert. |

| Werpt | Beschrijving |
| :- | :- |
| `ValueError` | Opgetreden wanneer `source_stream_provider` None is. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Initialiseert een nieuw [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) exemplaar.

Meer informatie

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | De methode die een leesbare stroom retourneert. |
| settings | `Func[ConverterSettings]` | De Converter-instellingen. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Initialiseert een nieuw [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) exemplaar.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable die een leesbare `io.RawIOBase` stream retourneert. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] die laadopties voor het document levert. De `LoadContext`-parameter bevat informatie over het document dat wordt geladen. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` die de converterinstellingen specificeert. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Initialiseert een nieuwe Converter met expliciete conversiegebeurtenissen.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable die een leesbare stream retourneert. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable die laadopties voor het document levert. |
| settings | `Func[ConverterSettings]` | Converter-instellingen. |
| events | `Func[ConversionEvents]` | Callable die geaggregeerde `ConversionEvents` levert die zijn geregistreerd voor de levensduur van de converter. |

## __init__ {#source_stream_provider-settings-events}

Initialiseert een nieuw Converter-exemplaar met expliciete conversiegebeurtenissen.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable die een leesbare stream retourneert. |
| settings | `Func[ConverterSettings]` | Converter-instellingen. |
| events | `Func[ConversionEvents]` | Delegate die geaggregeerde `ConversionEvents` levert die zijn geregistreerd voor de levensduur van de converter. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Initialiseert een nieuw Converter-exemplaar.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad naar het brondocument. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Initialiseert een nieuw [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) exemplaar.

Meer informatie

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad naar het brondocument. |
| settings | `Func[ConverterSettings]` | De Converter-instellingen. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Initialiseert een nieuw exemplaar van de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klasse.

Meer informatie

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad naar het brondocument. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate die laadopties voor het document levert. Handtekening: `Func<LoadContext, LoadOptions>`. De `LoadContext`-parameter bevat informatie over het document dat wordt geladen. |
| settings | `Func[ConverterSettings]` | De Converter-instellingen. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Initialiseert een nieuwe Converter met expliciete conversiegebeurtenissen.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad naar het brondocument. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate die laadopties voor het document levert. |
| settings | `Func[ConverterSettings]` | De Converter-instellingen. |
| events | `Func[ConversionEvents]` | Delegate die geaggregeerde `ConversionEvents` levert die zijn geregistreerd voor de levensduur van de converter. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Initialiseert een nieuwe Converter met expliciete conversiegebeurtenissen.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad naar het brondocument. |
| settings | `Func[ConverterSettings]` | De Converter-instellingen. |
| events | `Func[ConversionEvents]` | Delegate die geaggregeerde ConversionEvents levert die zijn geregistreerd voor de levensduur van de converter. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Zie ook
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
