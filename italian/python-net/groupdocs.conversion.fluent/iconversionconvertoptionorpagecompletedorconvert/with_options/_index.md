---
title: "metodo with_options"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Imposta le opzioni di conversione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
---


## with_options {#convert_options}

Imposta le opzioni di conversione.

```python
def with_options(self, convert_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Opzioni di conversione |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

Imposta le opzioni di conversione.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Opzioni di conversione. Il `ConvertContext` viene passato al provider. |

**Returns:** Interface to continue conversion building.

### Vedi anche
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
