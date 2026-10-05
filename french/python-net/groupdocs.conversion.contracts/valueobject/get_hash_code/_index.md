---
title: "méthode get_hash_code"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Servir de fonction de hachage par défaut."
type: docs
url: /fr/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

Servir de fonction de hachage par défaut.

Les composants de tableau, de liste et de dictionnaire sont hachés selon leur contenu, correspondant à la façon dont l'égalité les compare, de sorte que deux objets qui sont égaux sont également hachés de manière identique et peuvent être utilisés comme clés de dictionnaire ou membres d'ensemble.

Cela ne s'étend PAS à un composant qui est un autre `System.Collections.IEnumerable` : un tel composant est haché par référence, et celui exposé comme un itérateur paresseux renvoie une valeur différente à chaque accès, de sorte qu'un objet le contenant n'est pas du tout utilisable comme clé. Les collections imbriquées sont de même comparées et hachées par référence plutôt que de façon récursive.

L'autre conséquence est que la mutation d'une collection exposée par un objet valeur — ajouter à une liste de pages, ou écrire dans un tableau de noms de mise en page — modifie le hachage de cet objet, de sorte qu'une instance déjà stockée dans un conteneur de hachage devient inaccessible. Considérez un objet valeur comme figé une fois qu'il a été utilisé comme clé.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### Voir aussi
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
