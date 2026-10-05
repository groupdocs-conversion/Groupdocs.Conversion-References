---
title: "propriété detect_numbering_with_whitespaces"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "La propriété spécifie comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

La propriété indique comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut. La valeur par défaut est True.

Si cette option est définie sur False, l'algorithme de reconnaissance des listes détecte les paragraphes de listes lorsque les numéros de liste se terminent par un point, une parenthèse droite ou des symboles de puces (comme "•", "*", "-" ou "o").

Si cette option est définie sur True, les espaces sont également utilisés comme délimiteurs de numéros de liste : l'algorithme de reconnaissance des listes pour la numérotation de style arabe (par ex., 1., 1.1.2.) utilise à la fois les espaces et le point (".") comme symboles.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### Voir aussi
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
