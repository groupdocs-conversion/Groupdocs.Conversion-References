---
title: "метод convert"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Преобразует исходный документ и сохраняет весь преобразованный документ."
type: docs
url: /ru/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Преобразует исходный документ и сохраняет весь преобразованный документ.

Узнать больше:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Вызываемый объект, который получает поток и сохраняет в него преобразованный документ. |
| convert_options | `ConvertOptions` | Параметры преобразования, специфичные для требуемого типа целевого файла. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Создайте экземпляр Converter с входным документом
    with Converter("./business-plan.docx") as converter:
        # Определите параметры конвертации для вывода PDF
        pdf_options = PdfConvertOptions()
        # Преобразовать документ и сохранить как PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Преобразует исходный документ и сохраняет полностью преобразованный документ.

Узнать больше:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Параметры конвертации, специфичные для желаемого типа целевого файла. |
| document_completed | `Action[ConvertedContext]` | Делегат, получающий поток конвертированного документа. Сигнатура: `Action<ConvertedContext>`. Параметр `ConvertedContext` содержит поток конвертированного документа и метаданные. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Преобразует исходный документ и сохраняет полностью преобразованный документ.

Узнать больше:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase], предоставляющий поток для сохранения конвертированного документа. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions], предоставляющий параметры конвертации. |

**Returns:** None.

### Пример

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

Преобразует исходный документ и сохраняет полностью преобразованный документ.

Узнать больше

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] предоставляет параметры конвертации. Параметр `ConvertContext` содержит информацию о операции конвертации. |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] получает поток конвертированного документа. Параметр `ConvertedContext` содержит поток конвертированного документа и метаданные. |

**Returns:** None.

## convert {#file_path-convert_options}

Преобразует исходный документ и сохраняет полностью преобразованный документ.

Узнать больше:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к исходному документу. |
| convert_options | `ConvertOptions` | Параметры конвертации, специфичные для желаемого типа целевого файла. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Преобразует исходный документ и сохраняет преобразованный документ постранично.

Узнать больше

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase], предоставляющий поток для сохранения каждой конвертированной страницы. Параметр `SavePageContext` содержит номер страницы и информацию о документе. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions], предоставляющий параметры конвертации. Параметр `ConvertContext` содержит информацию о операции конвертации. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Преобразует исходный документ и сохраняет преобразованный документ постранично.

Узнать больше
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable, предоставляющий поток для сохранения каждой конвертированной страницы. Сигнатура: `Func<SavePageContext, Stream>`. Параметр `SavePageContext` содержит номер страницы и информацию о документе. |
| convert_options | `ConvertOptions` | Параметры конвертации, специфичные для желаемого типа целевого файла. |

**Returns:** None.

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Преобразует исходный документ и сохраняет преобразованный документ постранично.

Узнать больше

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Параметры конвертации, специфичные для желаемого типа целевого файла. |
| document_completed | `Action[ConvertedPageContext]` | Callable, получающий каждую конвертированную страницу. Параметр `ConvertedPageContext` содержит номер страницы, поток, имя исходного файла и тип целевого файла. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Преобразует исходный документ и сохраняет преобразованный документ постранично.

Узнать больше

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Делегат, предоставляющий параметры конвертации. Параметр `ConvertContext` содержит информацию о операции конвертации. |
| document_completed | `Action[ConvertedPageContext]` | Делегат, получающий каждую конвертированную страницу. Параметр `ConvertedPageContext` содержит номер страницы, поток, имя исходного файла и тип целевого файла. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### См. также
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
