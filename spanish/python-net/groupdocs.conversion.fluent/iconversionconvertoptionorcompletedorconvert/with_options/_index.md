---
title: "método with_options"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Establece opciones de conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/with_options/
is_root: false
weight: 1060
---


## with_options {#convert_options}

Establece opciones de conversión.

```python
def with_options(self, convert_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Opciones de conversión |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

Establece opciones de conversión.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Proveedor de opciones de conversión. convert_options_provider arg1arg1: El `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### Ver también
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
