---
title: "__init__‑Konstruktor"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von Converter."
type: docs
url: /de/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Initialisiert eine neue Instanz von Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Die Methode, die einen lesbaren Stream zurückgibt. |

| Wirft | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `source_stream_provider` None ist. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Initialisiert eine neue [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Instanz.

Mehr erfahren

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Die Methode, die einen lesbaren Stream zurückgibt. |
| settings | `Func[ConverterSettings]` | Die Converter‑Einstellungen. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Initialisiert eine neue [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Instanz.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable das einen lesbaren `io.RawIOBase`‑Stream zurückgibt. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] das Ladeoptionen für das Dokument bereitstellt. Der `LoadContext`‑Parameter enthält Informationen über das zu ladende Dokument. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` zur Angabe der Konverter‑Einstellungen. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Initialisiert einen neuen Converter mit expliziten Konvertierungsereignissen.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable das einen lesbaren Stream zurückgibt. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable, das Ladeoptionen für das Dokument bereitstellt. |
| settings | `Func[ConverterSettings]` | Konverter-Einstellungen. |
| events | `Func[ConversionEvents]` | Callable, das aggregierte `ConversionEvents` bereitstellt, die für die Lebensdauer des Konverters registriert sind. |

## __init__ {#source_stream_provider-settings-events}

Initialisiert eine neue Converter-Instanz mit expliziten Konvertierungsereignissen.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable das einen lesbaren Stream zurückgibt. |
| settings | `Func[ConverterSettings]` | Konverter-Einstellungen. |
| events | `Func[ConversionEvents]` | Delegate, das aggregierte `ConversionEvents` bereitstellt, die für die Lebensdauer des Konverters registriert sind. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Initialisiert eine neue Converter-Instanz.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad zum Quelldokument. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Initialisiert eine neue [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Instanz.

Mehr erfahren

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad zum Quelldokument. |
| settings | `Func[ConverterSettings]` | Die Converter‑Einstellungen. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Initialisiert eine neue Instanz der [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Klasse.

Mehr erfahren

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad zum Quelldokument. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate, das Ladeoptionen für das Dokument bereitstellt. Signatur: `Func<LoadContext, LoadOptions>`. Der Parameter `LoadContext` enthält Informationen über das zu ladende Dokument. |
| settings | `Func[ConverterSettings]` | Die Converter‑Einstellungen. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Initialisiert einen neuen Converter mit expliziten Konvertierungsereignissen.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad zum Quelldokument. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate, das Ladeoptionen für das Dokument bereitstellt. |
| settings | `Func[ConverterSettings]` | Die Converter‑Einstellungen. |
| events | `Func[ConversionEvents]` | Delegate, das aggregierte `ConversionEvents` bereitstellt, die für die Lebensdauer des Konverters registriert sind. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Initialisiert einen neuen Converter mit expliziten Konvertierungsereignissen.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad zum Quelldokument. |
| settings | `Func[ConverterSettings]` | Die Converter‑Einstellungen. |
| events | `Func[ConversionEvents]` | Delegate, das aggregierte ConversionEvents bereitstellt, die für die Lebensdauer des Konverters registriert sind. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Siehe auch
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
