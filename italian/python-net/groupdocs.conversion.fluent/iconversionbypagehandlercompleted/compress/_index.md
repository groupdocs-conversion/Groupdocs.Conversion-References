---
title: "metodo compress"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Comprime i risultati della conversione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

Comprime i risultati della conversione.

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
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
