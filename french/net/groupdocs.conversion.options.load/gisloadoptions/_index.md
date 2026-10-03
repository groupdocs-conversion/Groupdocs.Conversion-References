---
title: "GisLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents GIS."
type: docs
weight: 2540
url: /fr/net/groupdocs.conversion.options.load/gisloadoptions/
---
## GisLoadOptions class

Options de chargement des documents GIS.

```csharp
public class GisLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GisLoadOptions](gisloadoptions)() | Initialise une nouvelle instance de la classe [`GisLoadOptions`](../gisloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gisloadoptions/format) { get; set; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Définit la hauteur de page souhaitée pour la conversion du document GIS. La valeur par défaut est 1000. |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Définit la largeur de page souhaitée pour la conversion du document GIS. La valeur par défaut est 1000. |

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
