---
title: "propriété reason"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Le message de substitution exactement tel que rapporté par le pipeline de conversion, mot à mot et non analysé."
type: docs
url: /fr/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/
is_root: false
weight: 2020
---


## reason property

Le message de substitution exactement tel que rapporté par le pipeline de conversion, mot à mot et non analysé.

Pour les documents qui exposent les noms de police de manière structurée, cela peut être None (utilisez [`FontSubstitutionContext.original_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) / [`FontSubstitutionContext.substitute_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/)); pour les autres, il contient la description complète lisible par l'homme, qui indique à la fois la police manquante et la police de substitution.

### Definition:
```python
@property
def reason(self):
    ...
```

### Voir aussi
* class [`FontSubstitutionContext`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/)
