---
title: "metodo convert"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Converte il documento di origine e salva l'intero documento convertito."
type: docs
url: /it/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Converte il documento di origine e salva l'intero documento convertito.

Per saperne di più:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable che riceve uno stream e salva il documento convertito su di esso. |
| convert_options | `ConvertOptions` | Opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Istanzia Converter con il documento di input
    with Converter("./business-plan.docx") as converter:
        # Definisci le opzioni di conversione per l'output PDF
        pdf_options = PdfConvertOptions()
        # Converti il documento e salva come PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Converte il documento di origine e salva l'intero documento convertito.

Per saperne di più:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
| document_completed | `Action[ConvertedContext]` | Delegato che riceve lo stream del documento convertito. Firma: `Action<ConvertedContext>`. Il parametro `ConvertedContext` contiene lo stream del documento convertito e i metadati. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Converte il documento di origine e salva l'intero documento convertito.

Per saperne di più:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase] che fornisce lo stream per salvare il documento convertito. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] che fornisce le opzioni di conversione. |

**Returns:** None.

### Esempio

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

Converte il documento di origine e salva l'intero documento convertito.

Scopri di più

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] Fornisce le opzioni di conversione. Il parametro `ConvertContext` contiene informazioni sull'operazione di conversione. |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] Riceve lo stream del documento convertito. Il parametro `ConvertedContext` contiene lo stream del documento convertito e i metadati. |

**Returns:** None.

## convert {#file_path-convert_options}

Converte il documento di origine e salva l'intero documento convertito.

Per saperne di più:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file del documento sorgente. |
| convert_options | `ConvertOptions` | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Converte il documento di origine e salva il documento convertito pagina per pagina.

Scopri di più

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] che fornisce uno stream per salvare ogni pagina convertita. Il parametro `SavePageContext` contiene il numero di pagina e le informazioni del documento. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] che fornisce le opzioni di conversione. Il parametro `ConvertContext` contiene informazioni sull'operazione di conversione. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Converte il documento di origine e salva il documento convertito pagina per pagina.

Scopri di più
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable che fornisce uno stream per salvare ogni pagina convertita. Firma: `Func<SavePageContext, Stream>`. Il parametro `SavePageContext` contiene il numero di pagina e le informazioni del documento. |
| convert_options | `ConvertOptions` | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

**Returns:** None.

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Converte il documento di origine e salva il documento convertito pagina per pagina.

Scopri di più

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
| document_completed | `Action[ConvertedPageContext]` | Callable che riceve ogni pagina convertita. Il parametro `ConvertedPageContext` contiene il numero di pagina, lo stream, il nome del file sorgente e il tipo di file di destinazione. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Converte il documento di origine e salva il documento convertito pagina per pagina.

Scopri di più

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Delegato che fornisce le opzioni di conversione. Il parametro `ConvertContext` contiene informazioni sull'operazione di conversione. |
| document_completed | `Action[ConvertedPageContext]` | Delegato che riceve ogni pagina convertita. Il parametro `ConvertedPageContext` contiene il numero di pagina, lo stream, il nome del file sorgente e il tipo di file di destinazione. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Vedi anche
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
