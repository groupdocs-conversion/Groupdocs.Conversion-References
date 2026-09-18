---
title: __init__ constructor
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Initializes a new instance of Converter."
type: docs
url: /python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Initializes a new instance of Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | The method that returns a readable stream. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `source_stream_provider` is None. |

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Initializes a new [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instance.

Learn more

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | The method that returns a readable stream. |
| settings | `Func[ConverterSettings]` | The Converter settings. |

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Initializes a new [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instance.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable that returns a readable `io.RawIOBase` stream. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] that provides load options for the document. The `LoadContext` parameter contains information about the document being loaded. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` specifying the converter settings. |

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Initializes a new Converter with explicit conversion events.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable that returns a readable stream. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable that provides load options for the document. |
| settings | `Func[ConverterSettings]` | Converter settings. |
| events | `Func[ConversionEvents]` | Callable that provides aggregated `ConversionEvents` registered for the converter's lifetime. |

## __init__ {#source_stream_provider-settings-events}

Initializes a new Converter instance with explicit conversion events.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable that returns a readable stream. |
| settings | `Func[ConverterSettings]` | Converter settings. |
| events | `Func[ConversionEvents]` | Delegate providing aggregated `ConversionEvents` registered for the converter's lifetime. |

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Initializes a new Converter instance.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to the source document. |

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Initializes a new [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instance.

Learn more

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to the source document. |
| settings | `Func[ConverterSettings]` | The Converter settings. |

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Initializes new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class.

Learn more

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to the source document. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate that provides load options for the document. Signature: `Func<LoadContext, LoadOptions>`. The `LoadContext` parameter contains information about the document being loaded. |
| settings | `Func[ConverterSettings]` | The Converter settings. |

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Initializes a new Converter with explicit conversion events.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to the source document. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate that provides load options for the document. |
| settings | `Func[ConverterSettings]` | The Converter settings. |
| events | `Func[ConversionEvents]` | Delegate that provides aggregated `ConversionEvents` registered for the converter's lifetime. |

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Initializes a new Converter with explicit conversion events.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to the source document. |
| settings | `Func[ConverterSettings]` | The Converter settings. |
| events | `Func[ConversionEvents]` | Delegate that provides aggregated ConversionEvents registered for the converter's lifetime. |

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### See Also
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
