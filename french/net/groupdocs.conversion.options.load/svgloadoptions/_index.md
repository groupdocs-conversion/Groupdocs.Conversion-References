---
title: "SvgLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Svg."
type: docs
weight: 2830
url: /fr/net/groupdocs.conversion.options.load/svgloadoptions/
---
## SvgLoadOptions class

Options de chargement des documents Svg.

```csharp
public class SvgLoadOptions : LoadOptions, IResourceLoadingOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | Initialise une nouvelle instance de la classe [`SvgLoadOptions`](../svgloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [CropToContentBounds](../../groupdocs.conversion.options.load/svgloadoptions/croptocontentbounds) { get; set; } | Obtient ou définit une valeur indiquant s’il faut recadrer la boîte englobante SVG aux limites du contenu avant la conversion. La valeur par défaut est false. |
| [Format](../../groupdocs.conversion.options.load/svgloadoptions/format) { get; set; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [MinimumHeight](../../groupdocs.conversion.options.load/svgloadoptions/minimumheight) { get; set; } | Définit la hauteur minimale pour la conversion du document SVG. Elle est utilisée lors de la conversion vers des formats raster. La valeur par défaut est 600. |
| [MinimumWidth](../../groupdocs.conversion.options.load/svgloadoptions/minimumwidth) { get; set; } | Définit la largeur minimale pour la conversion du document SVG. Elle est utilisée lors de la conversion vers des formats raster. La valeur par défaut est 800. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/svgloadoptions/skipexternalresources) { get; set; } | Implémente [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/svgloadoptions/whitelistedresources) { get; set; } | Ressources externes qui seront toujours chargées. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [LoadOptions](../loadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
