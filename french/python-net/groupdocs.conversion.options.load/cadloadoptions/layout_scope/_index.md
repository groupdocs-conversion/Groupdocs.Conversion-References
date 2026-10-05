---
title: "propriété layout_scope"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Le périmètre de mise en page qui détermine quels espaces de dessin sont convertis."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

La portée de mise en page qui détermine quels espaces de dessin sont convertis. La valeur par défaut est [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), ce qui ne restreint pas la conversion. Ignorée lorsque [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) est fourni, car les noms de mise en page explicites l'emportent toujours. Une valeur `None` est traitée comme [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

Si le périmètre ne sélectionne aucune des feuilles proposées par un dessin, la conversion échoue avec `InvalidLoadOptionsException`, qui indique le périmètre et les feuilles disponibles au lieu de rendre les espaces exclus. Un dessin qui ne propose aucune feuille n’est pas affecté et se convertit toujours en une seule unité. Non pris en compte lors de la conversion vers PDF/UA-1, pour la raison indiquée sur [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### Voir aussi
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
