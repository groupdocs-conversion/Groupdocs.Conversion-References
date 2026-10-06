---
title: "método convert"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Convierte el documento de origen y guarda el documento convertido completo."
type: docs
url: /es/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Convierte el documento de origen y guarda el documento convertido completo.

Aprende más:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable que recibe un flujo y guarda el documento convertido en él. |
| convert_options | `ConvertOptions` | Opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Instanciar el Convertidor con el documento de entrada
    with Converter("./business-plan.docx") as converter:
        # Definir opciones de conversión para la salida PDF
        pdf_options = PdfConvertOptions()
        # Convierte el documento y guárdalo como PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Convierte el documento de origen y guarda todo el documento convertido.

Aprende más:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Las opciones de conversión específicas al tipo de archivo de destino deseado. |
| document_completed | `Action[ConvertedContext]` | Delegado que recibe el flujo del documento convertido. Firma: `Action<ConvertedContext>`. El parámetro `ConvertedContext` contiene el flujo del documento convertido y los metadatos. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Convierte el documento de origen y guarda todo el documento convertido.

Aprende más:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase] que proporciona el flujo para guardar el documento convertido. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] que proporciona opciones de conversión. |

**Returns:** None.

### Ejemplo

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

Convierte el documento de origen y guarda todo el documento convertido.

Más información

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] Proporciona opciones de conversión. El parámetro `ConvertContext` contiene información sobre la operación de conversión. |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] Recibe el flujo del documento convertido. El parámetro `ConvertedContext` contiene el flujo del documento convertido y los metadatos. |

**Returns:** None.

## convert {#file_path-convert_options}

Convierte el documento de origen y guarda todo el documento convertido.

Aprende más:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo al documento fuente. |
| convert_options | `ConvertOptions` | Las opciones de conversión específicas al tipo de archivo de destino deseado. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Convierte el documento de origen y guarda el documento convertido página por página.

Más información

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] que proporciona un flujo para guardar cada página convertida. El parámetro `SavePageContext` contiene el número de página y la información del documento. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] que proporciona opciones de conversión. El parámetro `ConvertContext` contiene información sobre la operación de conversión. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Convierte el documento de origen y guarda el documento convertido página por página.

Más información
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable que proporciona un flujo para guardar cada página convertida. Firma: `Func<SavePageContext, Stream>`. El parámetro `SavePageContext` contiene el número de página y la información del documento. |
| convert_options | `ConvertOptions` | Las opciones de conversión específicas al tipo de archivo de destino deseado. |

**Returns:** None.

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Convierte el documento de origen y guarda el documento convertido página por página.

Más información

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Las opciones de conversión específicas al tipo de archivo de destino deseado. |
| document_completed | `Action[ConvertedPageContext]` | Callable que recibe cada página convertida. El parámetro `ConvertedPageContext` contiene el número de página, el flujo, el nombre del archivo fuente y el tipo de archivo de destino. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Convierte el documento de origen y guarda el documento convertido página por página.

Más información

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Delegado que proporciona opciones de conversión. El parámetro `ConvertContext` contiene información sobre la operación de conversión. |
| document_completed | `Action[ConvertedPageContext]` | Delegado que recibe cada página convertida. El parámetro `ConvertedPageContext` contiene el número de página, el flujo, el nombre del archivo fuente y el tipo de archivo de destino. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Ver también
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
