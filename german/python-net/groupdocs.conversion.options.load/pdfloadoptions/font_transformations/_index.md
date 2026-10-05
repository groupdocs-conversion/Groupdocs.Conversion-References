---
title: "font_transformations Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Schriftarttransformationen, die nach dem Laden des Dokuments und dem Schriftartersatz angewendet werden und die Modifikation aller Schriftarten im Dokument ermöglichen, einschließlich der erfolgreich geladenen."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/pdfloadoptions/font_transformations/
is_root: false
weight: 2090
---


## font_transformations property

Die Schriftarttransformationen, die nach dem Laden des Dokuments und dem Schriftartersatz angewendet werden und die Modifikation aller Schriftarten im Dokument ermöglichen, einschließlich der erfolgreich geladenen.

Hinweis: Schrifttransformationen werden angewendet, nachdem alle Schrift-Ersetzungsschritte abgeschlossen sind.

Transformationen werden in der Reihenfolge verarbeitet, in der sie in der Liste erscheinen.

Anwendungsfälle: Stiländerungen, Markenanforderungen, Verbesserungen der Barrierefreiheit.

### Definition:
```python
@property
def font_transformations(self):
    ...
@font_transformations.setter
def font_transformations(self, value):
    ...
```

### Siehe auch
* class [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/)
