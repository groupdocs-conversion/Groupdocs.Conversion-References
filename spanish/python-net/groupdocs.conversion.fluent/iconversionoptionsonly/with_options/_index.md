---
title: "método with_options"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Establece opciones de conversión para el proceso de conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Establece opciones de conversión para el proceso de conversión.

```python
def with_options(self, convert_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Opciones de conversión. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Establece opciones de conversión usando una función proveedora.

```python
def with_options(self, options_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | Una función que proporciona opciones de conversión basadas en el contexto de conversión. |

**Returns:** Handler setup interface to continue conversion building.

### Ver también
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
