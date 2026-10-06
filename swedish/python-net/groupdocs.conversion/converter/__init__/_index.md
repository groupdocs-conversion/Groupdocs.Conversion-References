---
title: "__init__-konstruktor"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Initierar en ny instans av Converter."
type: docs
url: /sv/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Initierar en ny instans av Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Metoden som returnerar en läsbar ström. |

| Kastar | Beskrivning |
| :- | :- |
| `ValueError` | Kastas när `source_stream_provider` är None. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Initierar en ny [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instans.

Läs mer

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Metoden som returnerar en läsbar ström. |
| settings | `Func[ConverterSettings]` | Converter-inställningarna. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Initierar en ny [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instans.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Anropbar som returnerar en läsbar `io.RawIOBase`-ström. |
| load_options | `Func[LoadContext, LoadOptions]` | Anropbar [[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] som tillhandahåller laddningsalternativ för dokumentet. `LoadContext`‑parametern innehåller information om dokumentet som laddas. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` som specificerar konverteringsinställningarna. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Initierar en ny Converter med explicita konverteringshändelser.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Anropbar som returnerar en läsbar ström. |
| load_options | `Func[LoadContext, LoadOptions]` | Anropbar som tillhandahåller laddningsalternativ för dokumentet. |
| settings | `Func[ConverterSettings]` | Konverteringsinställningar. |
| events | `Func[ConversionEvents]` | Anropbar som tillhandahåller aggregerade `ConversionEvents` registrerade för konverterarens livstid. |

## __init__ {#source_stream_provider-settings-events}

Initierar en ny Converter-instans med explicita konverteringshändelser.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Anropbar som returnerar en läsbar ström. |
| settings | `Func[ConverterSettings]` | Konverteringsinställningar. |
| events | `Func[ConversionEvents]` | Delegat som tillhandahåller aggregerade `ConversionEvents` registrerade för konverterarens livstid. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Initierar en ny Converter-instans.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen till källdokumentet. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Initierar en ny [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instans.

Läs mer

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen till källdokumentet. |
| settings | `Func[ConverterSettings]` | Converter-inställningarna. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Initierar en ny instans av [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klass.

Läs mer

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen till källdokumentet. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegat som tillhandahåller laddningsalternativ för dokumentet. Signatur: `Func<LoadContext, LoadOptions>`. Parametern `LoadContext` innehåller information om dokumentet som laddas. |
| settings | `Func[ConverterSettings]` | Converter-inställningarna. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Initierar en ny Converter med explicita konverteringshändelser.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen till källdokumentet. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegat som tillhandahåller laddningsalternativ för dokumentet. |
| settings | `Func[ConverterSettings]` | Converter-inställningarna. |
| events | `Func[ConversionEvents]` | Delegat som tillhandahåller aggregerade `ConversionEvents` registrerade för konverterarens livstid. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Initierar en ny Converter med explicita konverteringshändelser.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen till källdokumentet. |
| settings | `Func[ConverterSettings]` | Converter-inställningarna. |
| events | `Func[ConversionEvents]` | Delegat som tillhandahåller aggregerade ConversionEvents registrerade för konverterarens livstid. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Se även
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
