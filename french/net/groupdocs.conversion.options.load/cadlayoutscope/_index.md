---
title: "CadLayoutScope"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Représente les espaces de dessin qu'une conversion CAD sélectionne : l'espace modèle, les mises en page de l'espace papier ou les deux."
type: docs
weight: 2420
url: /fr/net/groupdocs.conversion.options.load/cadlayoutscope/
---
## CadLayoutScope class

Représente les espaces de dessin qu'une conversion CAD sélectionne : l'espace modèle, les mises en page de l'espace papier, ou les deux.

```csharp
public class CadLayoutScope : Enumeration
```

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Détermine si deux instances d'objet sont égales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Both](../../groupdocs.conversion.options.load/cadlayoutscope/both) | Sélectionne l'espace modèle et chaque mise en page de l'espace papier. C'est la valeur par défaut et cela ne restreint pas la conversion : le dessin est rendu exactement comme il est lorsqu'aucune portée n'est exprimée. |
| static readonly [Layouts](../../groupdocs.conversion.options.load/cadlayoutscope/layouts) | Sélectionne uniquement les mises en page de l'espace papier. L'espace modèle est exclu. |
| static readonly [Model](../../groupdocs.conversion.options.load/cadlayoutscope/model) | Sélectionne uniquement l'espace modèle. |

### Voir aussi

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
