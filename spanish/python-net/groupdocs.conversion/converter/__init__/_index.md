---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Inicializa una nueva instancia de Converter."
type: docs
url: /es/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Inicializa una nueva instancia de Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | El método que devuelve un flujo legible. |

| Genera | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `source_stream_provider` es None. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Inicializa una nueva instancia de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Más información

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | El método que devuelve un flujo legible. |
| settings | `Func[ConverterSettings]` | La configuración del Converter. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Inicializa una nueva instancia de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable que devuelve un stream `io.RawIOBase` legible. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] que proporciona opciones de carga para el documento. El parámetro `LoadContext` contiene información sobre el documento que se está cargando. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` que especifica los ajustes del convertidor. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Inicializa un nuevo Converter con eventos de conversión explícitos.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable que devuelve un stream legible. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable que proporciona opciones de carga para el documento. |
| settings | `Func[ConverterSettings]` | Configuración del Converter. |
| events | `Func[ConversionEvents]` | Callable que proporciona `ConversionEvents` agregados registrados durante la vida del convertidor. |

## __init__ {#source_stream_provider-settings-events}

Inicializa una nueva instancia de Converter con eventos de conversión explícitos.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable que devuelve un stream legible. |
| settings | `Func[ConverterSettings]` | Configuración del Converter. |
| events | `Func[ConversionEvents]` | Delegate que proporciona `ConversionEvents` agregados registrados durante la vida del convertidor. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Inicializa una nueva instancia de Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo al documento fuente. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Inicializa una nueva instancia de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Más información

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo al documento fuente. |
| settings | `Func[ConverterSettings]` | La configuración del Converter. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Inicializa una nueva instancia de la clase [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Más información

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo al documento fuente. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate que proporciona opciones de carga para el documento. Firma: `Func<LoadContext, LoadOptions>`. El parámetro `LoadContext` contiene información sobre el documento que se está cargando. |
| settings | `Func[ConverterSettings]` | La configuración del Converter. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Inicializa un nuevo Converter con eventos de conversión explícitos.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo al documento fuente. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate que proporciona opciones de carga para el documento. |
| settings | `Func[ConverterSettings]` | La configuración del Converter. |
| events | `Func[ConversionEvents]` | Delegate que proporciona `ConversionEvents` agregados registrados durante la vida del convertidor. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Inicializa un nuevo Converter con eventos de conversión explícitos.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo al documento fuente. |
| settings | `Func[ConverterSettings]` | La configuración del Converter. |
| events | `Func[ConversionEvents]` | Delegate que proporciona ConversionEvents agregados registrados durante la vida del convertidor. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Ver también
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
