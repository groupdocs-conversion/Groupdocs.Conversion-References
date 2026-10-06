---
title: "propiedad auto_detect_rtl_direction"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La propiedad autodetectrtldirection determina si los párrafos y ejecuciones con texto predominantemente de derecha a izquierda tienen sus banderas bidi reparadas antes de la conversión."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

La propiedad auto_detect_rtl_direction determina si los párrafos y ejecuciones con texto predominantemente de derecha a izquierda tienen sus banderas bidi reparadas antes de la conversión.

Cuando se establece en True (por defecto), la propiedad aplica una heurística utilizada por Microsoft Word y LibreOffice, corrigiendo la representación de documentos árabes/hebreos generados por herramientas como Google Docs que emiten OOXML sin `<w:bidi/>` y con `<w:rtl w:val="0"/>` en ejecuciones que contienen solo script RTL. Establézcalo en False para preservar la interpretación estricta de OOXML del marcado fuente.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### Ver también
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
