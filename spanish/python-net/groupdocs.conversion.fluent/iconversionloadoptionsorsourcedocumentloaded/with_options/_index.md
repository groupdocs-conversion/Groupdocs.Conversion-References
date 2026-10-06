---
title: "método with_options"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Establecer opciones de carga."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/with_options/
is_root: false
weight: 1100
---


## with_options {#load_options}

Establecer opciones de carga.

```python
def with_options(self, load_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| load_options | `LoadOptions` | Opciones de carga |

## with_options {#load_options_provider}

Proporciona opciones de carga para el documento que se está cargando.

```python
def with_options(self, load_options_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Proveedor de opciones de carga. El contexto de opciones de carga. |

### Ver también
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
