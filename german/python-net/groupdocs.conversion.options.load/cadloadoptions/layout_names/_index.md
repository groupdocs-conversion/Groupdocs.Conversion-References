---
title: "layout_names Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die zu konvertierenden Layoutnamen."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

Die zu konvertierenden Layoutnamen.

Wird beim Konvertieren zu PDF/UA-1 nicht berücksichtigt. Dieses Ziel rendert die Zeichnung als eine einzelne getaggte Seite, die nicht ein Blatt pro ausgewähltem Layout enthalten kann, sodass stattdessen die gesamte Zeichnung konvertiert wird und hier nichts anwendbar ist.

Jedes andere Ziel, PDF eingeschlossen, berücksichtigt die Auswahl. Bei diesen Zielen werden Namen exakt mit den Layouts abgeglichen, die die Zeichnung enthält, sodass ein Name, der sich nur in der Groß‑/Kleinschreibung unterscheidet, ein anderer Name ist. Ein Name, der nichts findet, wird verworfen und kostet den Aufrufer nur dieses Blatt; eine Liste, in der nichts passt, lässt die Konvertierung mit einer `InvalidLoadOptionsException` fehlschlagen, die die fehlenden Namen und die Layouts, die die Zeichnung enthält, nennt, anstatt Blätter zu rendern, die der Aufrufer nicht angefordert hat. Eine Zeichnung, die überhaupt keine Layouts enthält, ist ausgenommen: Es gibt nichts, dem ein Name entsprechen könnte, sodass keiner abgelehnt wird.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### Siehe auch
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
