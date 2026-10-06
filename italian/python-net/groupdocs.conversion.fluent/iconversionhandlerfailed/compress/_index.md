---
title: "metodo compress"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Comprimi i risultati della conversione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/compress/
is_root: false
weight: 1010
---


## compress {#options}

Comprimi i risultati della conversione.

Registra un gestore di flusso compresso nella fase di ingresso tramite [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (impostando `OnCompressionCompleted`) invece di utilizzare il metodo di catena fluente obsoleto sull'interfaccia restituita.

```python
def compress(self, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Opzioni di conversione della compressione. |

**Returns:** Continuation that proceeds to `Convert`.

### Vedi anche
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
