---
title: "metodo with_options"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Imposta le opzioni di conversione per il processo di conversione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Imposta le opzioni di conversione per il processo di conversione.

```python
def with_options(self, convert_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Opzioni di conversione. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Imposta le opzioni di conversione utilizzando una funzione provider.

```python
def with_options(self, options_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | Una funzione che fornisce le opzioni di conversione basate sul contesto di conversione. |

**Returns:** Handler setup interface to continue conversion building.

### Vedi anche
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
