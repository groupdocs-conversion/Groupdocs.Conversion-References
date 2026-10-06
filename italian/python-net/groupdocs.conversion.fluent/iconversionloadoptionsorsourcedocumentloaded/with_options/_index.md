---
title: "metodo with_options"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Imposta le opzioni di caricamento."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/with_options/
is_root: false
weight: 1100
---


## with_options {#load_options}

Imposta le opzioni di caricamento.

```python
def with_options(self, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| load_options | `LoadOptions` | Opzioni di caricamento |

## with_options {#load_options_provider}

Fornisce le opzioni di caricamento per il documento attualmente in fase di caricamento.

```python
def with_options(self, load_options_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Provider delle opzioni di caricamento. Il contesto delle opzioni di caricamento. |

### Vedi anche
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
