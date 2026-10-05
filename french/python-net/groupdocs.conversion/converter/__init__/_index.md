---
title: "constructeur __init__"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Initialise une nouvelle instance de Converter."
type: docs
url: /fr/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Initialise une nouvelle instance de Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | La méthode qui renvoie un flux lisible. |

| Lève | Description |
| :- | :- |
| `ValueError` | Levée lorsque `source_stream_provider` est None. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Initialise une nouvelle instance de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

En savoir plus

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | La méthode qui renvoie un flux lisible. |
| settings | `Func[ConverterSettings]` | Les paramètres du Convertisseur. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Initialise une nouvelle instance de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable qui renvoie un flux `io.RawIOBase` lisible. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] qui fournit les options de chargement pour le document. Le paramètre `LoadContext` contient des informations sur le document en cours de chargement. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` spécifiant les paramètres du convertisseur. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Initialise un nouveau Converter avec des événements de conversion explicites.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable qui renvoie un flux lisible. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable qui fournit les options de chargement pour le document. |
| settings | `Func[ConverterSettings]` | Paramètres du convertisseur. |
| events | `Func[ConversionEvents]` | Callable qui fournit les `ConversionEvents` agrégés enregistrés pendant la durée de vie du convertisseur. |

## __init__ {#source_stream_provider-settings-events}

Initialise une nouvelle instance de Converter avec des événements de conversion explicites.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable qui renvoie un flux lisible. |
| settings | `Func[ConverterSettings]` | Paramètres du convertisseur. |
| events | `Func[ConversionEvents]` | Delegate fournissant les `ConversionEvents` agrégés enregistrés pendant la durée de vie du convertisseur. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Initialise une nouvelle instance de Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier du document source. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Initialise une nouvelle instance de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

En savoir plus

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier du document source. |
| settings | `Func[ConverterSettings]` | Les paramètres du Convertisseur. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Initialise une nouvelle instance de la classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

En savoir plus

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier du document source. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate qui fournit les options de chargement pour le document. Signature : `Func<LoadContext, LoadOptions>`. Le paramètre `LoadContext` contient des informations sur le document en cours de chargement. |
| settings | `Func[ConverterSettings]` | Les paramètres du Convertisseur. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Initialise un nouveau Converter avec des événements de conversion explicites.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier du document source. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate qui fournit les options de chargement pour le document. |
| settings | `Func[ConverterSettings]` | Les paramètres du Convertisseur. |
| events | `Func[ConversionEvents]` | Delegate qui fournit les `ConversionEvents` agrégés enregistrés pendant la durée de vie du convertisseur. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Initialise un nouveau Converter avec des événements de conversion explicites.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier du document source. |
| settings | `Func[ConverterSettings]` | Les paramètres du Convertisseur. |
| events | `Func[ConversionEvents]` | Delegate qui fournit les ConversionEvents agrégés enregistrés pendant la durée de vie du convertisseur. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Voir aussi
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
