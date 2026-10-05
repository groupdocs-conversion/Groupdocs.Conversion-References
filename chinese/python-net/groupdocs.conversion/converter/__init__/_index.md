---
title: "__init__ 构造函数"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "初始化 Converter 的新实例。"
type: docs
url: /zh/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

初始化 Converter 的新实例。

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 返回可读流的方法。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `source_stream_provider` 为 None 时抛出。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

初始化一个新的 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 实例。

了解更多

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 返回可读流的方法。 |
| settings | `Func[ConverterSettings]` | Converter 设置。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

初始化一个新的 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 实例。

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 可调用对象，返回可读取的 `io.RawIOBase` 流。 |
| load_options | `Func[LoadContext, LoadOptions]` | 可调用对象[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`]，提供文档的加载选项。`LoadContext` 参数包含有关正在加载的文档的信息。 |
| settings | `Func[ConverterSettings]` | `ConverterSettings` 指定转换器设置。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

使用显式转换事件初始化一个新的 Converter。

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 可调用对象，返回可读取的流。 |
| load_options | `Func[LoadContext, LoadOptions]` | 可调用对象，提供文档的加载选项。 |
| settings | `Func[ConverterSettings]` | 转换器设置。 |
| events | `Func[ConversionEvents]` | 可调用对象，提供在转换器生命周期内注册的聚合 `ConversionEvents`。 |

## __init__ {#source_stream_provider-settings-events}

使用显式转换事件初始化一个新的 Converter 实例。

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 可调用对象，返回可读取的流。 |
| settings | `Func[ConverterSettings]` | 转换器设置。 |
| events | `Func[ConversionEvents]` | 委托，提供在转换器生命周期内注册的聚合 `ConversionEvents`。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

初始化一个新的 Converter 实例。

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 源文档的文件路径。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

初始化一个新的 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 实例。

了解更多

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 源文档的文件路径。 |
| settings | `Func[ConverterSettings]` | Converter 设置。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

初始化 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 类的新实例。

了解更多

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 源文档的文件路径。 |
| load_options | `Func[LoadContext, LoadOptions]` | 委托，提供文档的加载选项。签名：`Func<LoadContext, LoadOptions>`。`LoadContext` 参数包含有关正在加载的文档的信息。 |
| settings | `Func[ConverterSettings]` | Converter 设置。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

使用显式转换事件初始化一个新的 Converter。

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 源文档的文件路径。 |
| load_options | `Func[LoadContext, LoadOptions]` | 委托，提供文档的加载选项。 |
| settings | `Func[ConverterSettings]` | Converter 设置。 |
| events | `Func[ConversionEvents]` | 委托，提供在转换器生命周期内注册的聚合 `ConversionEvents`。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

使用显式转换事件初始化一个新的 Converter。

```python
def __init__(self, file_path, settings, events):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 源文档的文件路径。 |
| settings | `Func[ConverterSettings]` | Converter 设置。 |
| events | `Func[ConversionEvents]` | 委托，提供在转换器生命周期内注册的聚合 ConversionEvents。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### 另见
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
