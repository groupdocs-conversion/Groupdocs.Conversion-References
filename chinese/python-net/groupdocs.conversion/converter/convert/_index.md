---
title: "convert 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "转换源文档并保存整个转换后的文档。"
type: docs
url: /zh/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

转换源文档并保存整个转换后的文档。

了解更多：
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | 可调用对象，接收流并将转换后的文档保存到其中。 |
| convert_options | `ConvertOptions` | 特定于所需目标文件类型的转换选项。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # 使用输入文档实例化 Converter
    with Converter("./business-plan.docx") as converter:
        # 为 PDF 输出定义转换选项
        pdf_options = PdfConvertOptions()
        # 将文档转换并保存为 PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

转换源文档并保存完整的转换后文档。

了解更多：
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 特定于所需目标文件类型的转换选项。 |
| document_completed | `Action[ConvertedContext]` | 接收已转换文档流的委托。签名：`Action<ConvertedContext>`。`ConvertedContext` 参数包含已转换的文档流和元数据。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

转换源文档并保存完整的转换后文档。

了解更多：
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase]，提供用于保存转换后文档的流。 |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions]，提供转换选项。 |

**Returns:** None.

### 示例

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

转换源文档并保存完整的转换后文档。

了解更多

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] 提供转换选项。`ConvertContext` 参数包含有关转换操作的信息。 |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] 接收转换后的文档流。`ConvertedContext` 参数包含转换后文档的流和元数据。 |

**Returns:** None.

## convert {#file_path-convert_options}

转换源文档并保存完整的转换后文档。

了解更多：
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 源文档的文件路径。 |
| convert_options | `ConvertOptions` | 针对所需目标文件类型的转换选项。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

逐页转换源文档并保存转换后的文档。

了解更多

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase]，提供用于保存每个转换页面的流。`SavePageContext` 参数包含页码和文档信息。 |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions]，提供转换选项。`ConvertContext` 参数包含有关转换操作的信息。 |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

逐页转换源文档并保存转换后的文档。

了解更多
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable，提供用于保存每个转换页面的流。签名：`Func<SavePageContext, Stream>`。`SavePageContext` 参数包含页码和文档信息。 |
| convert_options | `ConvertOptions` | 针对所需目标文件类型的转换选项。 |

**Returns:** None.

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

逐页转换源文档并保存转换后的文档。

了解更多

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 特定于所需目标文件类型的转换选项。 |
| document_completed | `Action[ConvertedPageContext]` | Callable，接收每个转换页面。`ConvertedPageContext` 参数包含页码、流、源文件名和目标文件类型。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

逐页转换源文档并保存转换后的文档。

了解更多

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Delegate，提供转换选项。`ConvertContext` 参数包含有关转换操作的信息。 |
| document_completed | `Action[ConvertedPageContext]` | Delegate，接收每个转换页面。`ConvertedPageContext` 参数包含页码、流、源文件名和目标文件类型。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### 另见
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
