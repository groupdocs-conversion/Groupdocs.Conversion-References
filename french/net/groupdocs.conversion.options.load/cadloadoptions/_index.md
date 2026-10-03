---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents CAD."
type: docs
weight: 2430
url: /fr/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

Options de chargement des documents CAD.

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | Initialise une nouvelle instance de la classe [`CadLoadOptions`](../cadloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | Obtient ou définit une couleur d'arrière-plan. |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | Obtient ou définit les sources CTB. |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | Obtient ou définit la couleur de premier plan. |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | Obtient ou définit le type de dessin. |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | Spécifie quels agencements CAD doivent être convertis |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | Obtient ou définit quels espaces de dessin sont convertis. La valeur par défaut est [`Both`](../cadlayoutscope/both), qui ne restreint pas la conversion. Elle est ignorée lorsque [`LayoutNames`](./layoutnames) est fourni, car les noms d'agencements explicites prévalent toujours. Une valeur `null` est traitée comme [`Both`](../cadlayoutscope/both). |

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
