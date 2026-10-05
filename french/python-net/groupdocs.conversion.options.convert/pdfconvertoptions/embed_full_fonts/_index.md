---
title: "embed_full_fonts propriété"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "La propriété détermine si le fichier de police complet est intégré dans le PDF au lieu d’un sous-ensemble."
type: docs
url: /fr/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/
is_root: false
weight: 2020
---


## embed_full_fonts property

La propriété détermine si le fichier de police complet est intégré dans le PDF au lieu d’un sous-ensemble.

Lorsque définie sur True, la taille du fichier de sortie augmente mais assure une meilleure compatibilité lors de l'édition du PDF résultant. S'applique uniquement lors de la conversion à partir de documents WordProcessing.

### Definition:
```python
@property
def embed_full_fonts(self):
    ...
@embed_full_fonts.setter
def embed_full_fonts(self, value):
    ...
```

### Voir aussi
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
