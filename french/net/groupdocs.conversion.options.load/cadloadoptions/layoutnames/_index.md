---
title: "LayoutNames"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Spécifie quels agencements CAD doivent être convertis"
type: docs
weight: 70
url: /fr/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

Spécifie quels agencements CAD doivent être convertis

```csharp
public string[] LayoutNames { get; set; }
```

### Remarques

Non respecté lors de la conversion vers PDF/UA-1. Cette cible rend le dessin sous forme d’une seule page balisée, qui ne peut pas contenir une feuille par mise en page sélectionnée, ainsi le dessin complet est converti à la place et rien ici ne s’applique. Toutes les autres cibles, PDF inclus, respectent la sélection. Sur ces cibles, les noms sont comparés exactement aux mises en page que le dessin possède, de sorte qu’un nom qui ne diffère que par la casse est considéré comme un nom différent. Un nom qui ne correspond à rien est ignoré et ne coûte à l’appelant que cette feuille ; une liste dans laquelle aucun nom ne correspond entraîne l’échec de la conversion avec une [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) indiquant les noms manquants et les mises en page que le dessin possède, plutôt que de rendre des feuilles que l’appelant n’a pas demandées. Un dessin qui ne possède aucune mise en page est exempté : il n’y a rien à faire correspondre, donc aucun n’est refusé.

### Voir aussi

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
