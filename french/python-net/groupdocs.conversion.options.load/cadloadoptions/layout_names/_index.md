---
title: "propriété layout_names"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Les noms de mise en page à convertir."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

Les noms de mise en page à convertir.

Non respecté lors de la conversion vers PDF/UA-1. Cette cible rend le dessin comme une seule page balisée, qui ne peut pas contenir une feuille par mise en page sélectionnée, ainsi le dessin complet est converti à la place et rien ici ne s'applique.

Tous les autres cibles, PDF inclus, respectent la sélection. Sur ces cibles, les noms sont comparés exactement aux mises en page que le dessin possède, de sorte qu'un nom qui ne diffère que par la casse est un nom différent. Un nom qui ne correspond à rien est ignoré et ne coûte à l'appelant que cette feuille ; une liste dans laquelle rien ne correspond entraîne l'échec de la conversion avec une `InvalidLoadOptionsException` indiquant les noms manquants et les mises en page que le dessin possède, plutôt que de rendre des feuilles que l'appelant n'a pas demandées. Un dessin qui ne possède aucune mise en page est exempté : il n'y a rien que le nom puisse correspondre, donc aucun n'est refusé.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### Voir aussi
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
