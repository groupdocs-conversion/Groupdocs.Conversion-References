---
title: "layout_scope Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Der Layout‑Umfang, der bestimmt, welche Zeichenbereiche konvertiert werden."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

Der Layout‑Bereich, der bestimmt, welche Zeichenbereiche konvertiert werden. Standardmäßig ist [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), was die Konvertierung nicht einschränkt. Ignoriert, wenn [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) angegeben ist, weil explizite Layoutnamen immer Vorrang haben. Ein `None`‑Wert wird als [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/) behandelt.

Wenn der Umfang keine der von einer Zeichnung angebotenen Blätter auswählt, schlägt die Konvertierung mit einer `InvalidLoadOptionsException` fehl, die den Umfang und die verfügbaren Blätter nennt, anstatt die ausgeschlossenen Bereiche zu rendern. Eine Zeichnung, die überhaupt kein Blatt anbietet, bleibt unverändert und wird weiterhin als eine Einheit konvertiert. Wird beim Konvertieren zu PDF/UA-1 nicht berücksichtigt, aus dem Grund, der unter [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) angegeben ist.

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### Siehe auch
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
