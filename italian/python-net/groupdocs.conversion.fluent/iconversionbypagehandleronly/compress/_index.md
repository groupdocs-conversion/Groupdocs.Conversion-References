---
title: "metodo compress"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Comprimi i risultati della conversione; registra un gestore di flusso compresso nella fase di ingresso tramite IConversionSettings.withevents (impostando OnCompressionCompleted) invece di utilizzare il fluente obsoleto…"
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Comprime i risultati della conversione; registra un gestore di stream compresso nella fase di ingresso tramite [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (impostando `OnCompressionCompleted`) invece di utilizzare il metodo della catena fluida obsoleto.

```python
def compress(self, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Opzioni di conversione della compressione. |

**Returns:** Continuation that proceeds to `Convert`.

### Vedi anche
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
