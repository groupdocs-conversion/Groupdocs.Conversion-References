---
title: "método compress"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Comprime los resultados de la conversión; registre un controlador de flujo comprimido en la etapa de entrada mediante IConversionSettings.withevents (configurando OnCompressionCompleted) en lugar de usar el método fluido obsoleto…"
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Comprime los resultados de la conversión; registre un controlador de flujo comprimido en la etapa de entrada mediante [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (estableciendo `OnCompressionCompleted`) en lugar de usar el método de cadena fluida obsoleto.

```python
def compress(self, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Opciones de conversión de compresión. |

**Returns:** Continuation that proceeds to `Convert`.

### Ver también
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
