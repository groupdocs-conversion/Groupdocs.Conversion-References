---
title: "DetectNumberingWithWhitespaces"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Permet de spécifier comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut. La valeur par défaut est true."
type: docs
weight: 30
url: /fr/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

Permet de spécifier comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut. La valeur par défaut est true.

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### Remarques

Si cette option est définie sur false, l'algorithme de reconnaissance des listes détecte les paragraphes de listes lorsque les numéros de liste se terminent par un point, une parenthèse droite ou des symboles de puces (comme \"•\", \"*\", \"-\" ou \"o\").

Si cette option est définie sur true, les espaces sont également utilisés comme délimiteurs de numéros de liste : l'algorithme de reconnaissance des listes pour la numérotation de style arabe (1., 1.1.2.) utilise à la fois les espaces et le symbole point (\".\").

### Voir aussi

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
