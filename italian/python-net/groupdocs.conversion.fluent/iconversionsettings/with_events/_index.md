---
title: "metodo with_events"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Registra i gestori di eventi del ciclo di vita della conversione su un contenitore ConversionEvents che vive per tutta la durata del convertitore e si attiva ad ogni esecuzione di conversione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

Registra i gestori degli eventi del ciclo di vita della conversione su un sacchetto [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) che vive per tutta la durata del convertitore e si attiva ad ogni esecuzione di conversione.

Si trova allo stesso stadio di ingresso di [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). Le chiamate multiple si accumulano: lo stesso contenitore interno viene passato a ogni azione `configure`, quindi i gestori impostati nelle chiamate precedenti rimangono a meno che non vengano sovrascritti da una successiva.

```python
def with_events(self, configure):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Azione che modifica il contenitore degli eventi. |

**Returns:** The source-selection stage so that `Load` may be chained.

### Vedi anche
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
