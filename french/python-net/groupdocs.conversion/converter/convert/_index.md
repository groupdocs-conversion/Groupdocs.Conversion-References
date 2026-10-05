---
title: "méthode convert"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Convertit le document source et enregistre le document converti complet."
type: docs
url: /fr/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Convertit le document source et enregistre le document converti complet.

En savoir plus :
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Objet appelable qui reçoit un flux et y enregistre le document converti. |
| convert_options | `ConvertOptions` | Options de conversion spécifiques au type de fichier cible souhaité. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Instanciez le Convertisseur avec le document d'entrée
    with Converter("./business-plan.docx") as converter:
        # Définissez les options de conversion pour la sortie PDF
        pdf_options = PdfConvertOptions()
        # Convertir le document et l'enregistrer au format PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Convertit le document source et enregistre le document converti entier.

En savoir plus :
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Les options de conversion spécifiques au type de fichier cible souhaité. |
| document_completed | `Action[ConvertedContext]` | Délégation qui reçoit le flux du document converti. Signature : `Action<ConvertedContext>`. Le paramètre `ConvertedContext` contient le flux du document converti et les métadonnées. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Convertit le document source et enregistre le document converti entier.

En savoir plus :
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase] qui fournit le flux pour enregistrer le document converti. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] qui fournit les options de conversion. |

**Returns:** None.

### Exemple

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

Convertit le document source et enregistre le document converti entier.

En savoir plus

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] fournit les options de conversion. Le paramètre `ConvertContext` contient des informations sur l'opération de conversion. |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] reçoit le flux du document converti. Le paramètre `ConvertedContext` contient le flux du document converti et les métadonnées. |

**Returns:** None.

## convert {#file_path-convert_options}

Convertit le document source et enregistre le document converti entier.

En savoir plus :
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier du document source. |
| convert_options | `ConvertOptions` | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Convertit le document source et enregistre le document converti page par page.

En savoir plus

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] qui fournit un flux pour enregistrer chaque page convertie. Le paramètre `SavePageContext` contient le numéro de page et les informations du document. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] qui fournit les options de conversion. Le paramètre `ConvertContext` contient des informations sur l'opération de conversion. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Convertit le document source et enregistre le document converti page par page.

En savoir plus
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable qui fournit un flux pour enregistrer chaque page convertie. Signature : `Func<SavePageContext, Stream>`. Le paramètre `SavePageContext` contient le numéro de page et les informations du document. |
| convert_options | `ConvertOptions` | Les options de conversion spécifiques au type de fichier cible souhaité. |

**Returns:** None.

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Convertit le document source et enregistre le document converti page par page.

En savoir plus

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Les options de conversion spécifiques au type de fichier cible souhaité. |
| document_completed | `Action[ConvertedPageContext]` | Callable qui reçoit chaque page convertie. Le paramètre `ConvertedPageContext` contient le numéro de page, le flux, le nom du fichier source et le type de fichier cible. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Convertit le document source et enregistre le document converti page par page.

En savoir plus

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Délégation qui fournit les options de conversion. Le paramètre `ConvertContext` contient des informations sur l'opération de conversion. |
| document_completed | `Action[ConvertedPageContext]` | Délégation qui reçoit chaque page convertie. Le paramètre `ConvertedPageContext` contient le numéro de page, le flux, le nom du fichier source et le type de fichier cible. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Voir aussi
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
