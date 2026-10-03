---
title: "Rectangle"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Représente un rectangle défini par ses bords à des fins de recadrage."
type: docs
weight: 580
url: /fr/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

Représente un rectangle défini par ses bords à des fins de recadrage.

```csharp
public sealed class Rectangle : ValueObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | Initialise une nouvelle instance de la structure [`Rectangle`](../rectangle) avec les bords spécifiés. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | Obtient le bord inférieur du rectangle. |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | Obtient la hauteur du rectangle en fonction des bords supérieur et inférieur. |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | Obtient le bord gauche du rectangle. |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | Obtient le bord droit du rectangle. |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | Obtient le bord supérieur du rectangle. |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | Obtient la largeur du rectangle en fonction des bords gauche et droit. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | Crée une version recadrée du rectangle actuel en supprimant les marges spécifiées. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | Renvoie une représentation sous forme de chaîne du rectangle. |

### Voir aussi

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
