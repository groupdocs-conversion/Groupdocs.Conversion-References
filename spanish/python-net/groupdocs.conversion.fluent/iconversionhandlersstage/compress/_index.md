---
title: "método compress"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Comprime los resultados de la conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/
is_root: false
weight: 1010
---


## compress {#options}

Comprime los resultados de la conversión.

Registre un controlador de flujo comprimido en la etapa de entrada mediante [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (configurando `OnCompressionCompleted`) en lugar de usar el método de cadena fluida obsoleto en la interfaz devuelta.

```python
def compress(self, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Opciones de conversión de compresión |

**Returns:** Continuation that proceeds to `Convert`.

### Ver también
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
