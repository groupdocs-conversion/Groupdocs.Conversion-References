---
title: "metodo with_options"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Imposta le opzioni di caricamento."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

Imposta le opzioni di caricamento.

```python
def with_options(self, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| load_options | `LoadOptions` | Opzioni di caricamento. |

## with_options {#load_options_provider}

Fornisce le opzioni di caricamento per il documento attualmente in fase di caricamento.

```python
def with_options(self, load_options_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Provider di opzioni di caricamento. Il provider riceve il contesto delle opzioni di caricamento. |

### Vedi anche
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
