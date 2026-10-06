---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Inizializza una nuova istanza di Converter."
type: docs
url: /it/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Inizializza una nuova istanza di Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Il metodo che restituisce uno stream leggibile. |

| Genera | Descrizione |
| :- | :- |
| `ValueError` | Sollevata quando `source_stream_provider` è None. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Inizializza una nuova istanza di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Scopri di più

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Il metodo che restituisce uno stream leggibile. |
| settings | `Func[ConverterSettings]` | Le impostazioni del Converter. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Inizializza una nuova istanza di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable che restituisce uno stream leggibile `io.RawIOBase`. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] che fornisce le opzioni di caricamento per il documento. Il parametro `LoadContext` contiene informazioni sul documento in fase di caricamento. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` che specifica le impostazioni del convertitore. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Inizializza un nuovo Converter con eventi di conversione espliciti.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable che restituisce uno stream leggibile. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable che fornisce le opzioni di caricamento per il documento. |
| settings | `Func[ConverterSettings]` | Impostazioni del Converter. |
| events | `Func[ConversionEvents]` | Callable che fornisce `ConversionEvents` aggregati registrati per la durata del converter. |

## __init__ {#source_stream_provider-settings-events}

Inizializza una nuova istanza di Converter con eventi di conversione espliciti.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable che restituisce uno stream leggibile. |
| settings | `Func[ConverterSettings]` | Impostazioni del Converter. |
| events | `Func[ConversionEvents]` | Delegate che fornisce `ConversionEvents` aggregati registrati per la durata del converter. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Inizializza una nuova istanza di Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file del documento sorgente. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Inizializza una nuova istanza di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Scopri di più

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file del documento sorgente. |
| settings | `Func[ConverterSettings]` | Le impostazioni del Converter. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Inizializza una nuova istanza della classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Scopri di più

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file del documento sorgente. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate che fornisce le opzioni di caricamento per il documento. Firma: `Func<LoadContext, LoadOptions>`. Il parametro `LoadContext` contiene informazioni sul documento in fase di caricamento. |
| settings | `Func[ConverterSettings]` | Le impostazioni del Converter. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Inizializza un nuovo Converter con eventi di conversione espliciti.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file del documento sorgente. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate che fornisce le opzioni di caricamento per il documento. |
| settings | `Func[ConverterSettings]` | Le impostazioni del Converter. |
| events | `Func[ConversionEvents]` | Delegate che fornisce `ConversionEvents` aggregati registrati per la durata del converter. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Inizializza un nuovo Converter con eventi di conversione espliciti.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file del documento sorgente. |
| settings | `Func[ConverterSettings]` | Le impostazioni del Converter. |
| events | `Func[ConversionEvents]` | Delegate che fornisce ConversionEvents aggregati registrati per la durata del converter. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Vedi anche
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
