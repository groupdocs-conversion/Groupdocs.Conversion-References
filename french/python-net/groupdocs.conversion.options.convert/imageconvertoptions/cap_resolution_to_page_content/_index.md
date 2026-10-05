---
title: "propriété cap_resolution_to_page_content"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "La propriété limite la résolution de rendu PDF par page à la résolution raster native de la page, empêchant un rendu à un DPI supérieur à celui de l'image incorporée et émettant la page à sa résolution native (plus petite)…"
type: docs
url: /fr/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

La propriété limite la résolution de rendu PDF par page à la résolution raster native de la page, empêchant le rendu à un DPI supérieur à celui de l'image intégrée et émettant la page à ses dimensions de pixels natives (plus petites) et DPI dans le résultat final.

Seules les pages dominées par des images (numérisation) sont affectées ; les pages contenant du texte ou du contenu vectoriel ne sont jamais adoucies et sont émises au DPI demandé. La limitation est ignorée lorsqu'une sortie explicite [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) ou [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) est définie. La valeur par défaut est False (pas de limitation ; chaque page est rendue et émise au DPI demandé).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### Voir aussi
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
