---
title: "конструктор __init__"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Инициализирует новый экземпляр Converter."
type: docs
url: /ru/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Инициализирует новый экземпляр Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Метод, возвращающий читаемый поток. |

| Вызывает | Описание |
| :- | :- |
| `ValueError` | Возникает, когда `source_stream_provider` равен None. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Инициализирует новый экземпляр [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Узнать больше

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Метод, возвращающий читаемый поток. |
| settings | `Func[ConverterSettings]` | Настройки конвертера. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Инициализирует новый экземпляр [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Вызываемый объект, который возвращает читаемый поток `io.RawIOBase`. |
| load_options | `Func[LoadContext, LoadOptions]` | Вызываемый объект [[`LoadContext`], `GroupDocs.Conversion.LoadOptions`], который предоставляет параметры загрузки для документа. Параметр `LoadContext` содержит информацию о загружаемом документе. |
| settings | `Func[ConverterSettings]` | `ConverterSettings`, определяющий настройки конвертера. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Инициализирует новый Converter с явными событиями конвертации.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Вызываемый объект, который возвращает читаемый поток. |
| load_options | `Func[LoadContext, LoadOptions]` | Вызываемый объект, который предоставляет параметры загрузки для документа. |
| settings | `Func[ConverterSettings]` | Настройки конвертера. |
| events | `Func[ConversionEvents]` | Вызываемый объект, который предоставляет агрегированные `ConversionEvents`, зарегистрированные на протяжении жизни конвертера. |

## __init__ {#source_stream_provider-settings-events}

Инициализирует новый экземпляр Converter с явными событиями конвертации.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Вызываемый объект, который возвращает читаемый поток. |
| settings | `Func[ConverterSettings]` | Настройки конвертера. |
| events | `Func[ConversionEvents]` | Делегат, предоставляющий агрегированные `ConversionEvents`, зарегистрированные на протяжении жизни конвертера. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Инициализирует новый экземпляр Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к исходному документу. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Инициализирует новый экземпляр [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Узнать больше

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к исходному документу. |
| settings | `Func[ConverterSettings]` | Настройки конвертера. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Инициализирует новый экземпляр класса [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Узнать больше

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к исходному документу. |
| load_options | `Func[LoadContext, LoadOptions]` | Делегат, который предоставляет параметры загрузки для документа. Сигнатура: `Func<LoadContext, LoadOptions>`. Параметр `LoadContext` содержит информацию о загружаемом документе. |
| settings | `Func[ConverterSettings]` | Настройки конвертера. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Инициализирует новый Converter с явными событиями конвертации.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к исходному документу. |
| load_options | `Func[LoadContext, LoadOptions]` | Делегат, который предоставляет параметры загрузки для документа. |
| settings | `Func[ConverterSettings]` | Настройки конвертера. |
| events | `Func[ConversionEvents]` | Делегат, который предоставляет агрегированные `ConversionEvents`, зарегистрированные на протяжении жизни конвертера. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Инициализирует новый Converter с явными событиями конвертации.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к исходному документу. |
| settings | `Func[ConverterSettings]` | Настройки конвертера. |
| events | `Func[ConversionEvents]` | Делегат, который предоставляет агрегированные ConversionEvents, зарегистрированные на протяжении жизни конвертера. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### См. также
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
