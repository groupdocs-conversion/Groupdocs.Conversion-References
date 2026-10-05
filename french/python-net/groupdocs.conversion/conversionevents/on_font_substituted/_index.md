---
title: "propriété on_font_substituted"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "L'événement déclenché lorsqu'une police référencée par le document source n'est pas disponible et est substituée (soit par une règle FontSubstitute fournie par le client, soit par la police par défaut configurée, ou par le…"
type: docs
url: /fr/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

L'événement déclenché lorsqu'une police référencée par le document source n'est pas disponible et est substituée (soit par une règle fournie par le client [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/), soit par la police par défaut configurée, ou par le mécanisme de secours interne du pipeline de conversion).

L'événement est dédupliqué par `(SourceFileName, OriginalFontName)` au sein d'un seul appel `Converter.Convert(...)` — les abonnés reçoivent au maximum une notification par police manquante pour chaque document source. Il se déclenche de façon synchrone sur le thread de conversion. Il n'est pas déclenché pour les conversions d'images.

Pour les documents de présentation, la substitution de police n'est détectée que sous Windows, car le moteur la résout via une correspondance de polices spécifique à la plateforme qui n'est pas disponible sur les autres systèmes d'exploitation.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### Voir aussi
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
