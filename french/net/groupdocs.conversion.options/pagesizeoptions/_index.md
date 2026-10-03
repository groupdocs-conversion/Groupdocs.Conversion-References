---
title: "PageSizeOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Représente les options qui prennent en charge la taille de la page."
type: docs
weight: 2990
url: /fr/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

Représente les options qui prennent en charge la taille de la page.

```csharp
public sealed class PageSizeOptions : ValueObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | Constructeur par défaut. Initialise [`PageSize`](./pagesize) à [`Unset`](../pagesize/unset). |

## Propriétés

| Nom | Description |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | Hauteur de page en points à appliquer avant la conversion. Lorsqu'elle est définie, [`PageSize`](./pagesize) est automatiquement changée en [`Custom`](../pagesize/custom). |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | Implémente [`PageSize`](../pagesize) |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | Largeur de page en points à appliquer avant la conversion. Lorsqu'elle est définie, [`PageSize`](./pagesize) est automatiquement changée en [`Custom`](../pagesize/custom). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
