---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Diagram."
type: docs
weight: 2470
url: /fr/net/groupdocs.conversion.options.load/diagramloadoptions/
---
## DiagramLoadOptions class

Options de chargement des documents Diagram.

```csharp
public sealed class DiagramLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DiagramLoadOptions](diagramloadoptions)() | Initialise une nouvelle instance de la classe [`DiagramLoadOptions`](../diagramloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/diagramloadoptions/defaultfont) { get; set; } | Police par défaut pour le document Diagram. La police suivante sera utilisée si une police est manquante. |
| [Format](../../groupdocs.conversion.options.load/diagramloadoptions/format) { get; set; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
