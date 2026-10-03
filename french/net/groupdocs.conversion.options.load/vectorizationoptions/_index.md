---
title: "VectorizationOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de vectorisation des images."
type: docs
weight: 2900
url: /fr/net/groupdocs.conversion.options.load/vectorizationoptions/
---
## VectorizationOptions class

Options de vectorisation des images.

```csharp
public class VectorizationOptions : ValueObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VectorizationOptions](vectorizationoptions)() | Constructeur par défaut pour VectorizationOptions. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/vectorizationoptions/backgroundcolor) { get; set; } | Obtient ou définit la couleur d'arrière-plan. La valeur par défaut est blanc transparent. |
| [ColorsLimit](../../groupdocs.conversion.options.load/vectorizationoptions/colorslimit) { get; set; } | Obtient ou définit le nombre maximal de couleurs utilisées pour quantifier une image. La valeur par défaut est 25. |
| [EnableVectorization](../../groupdocs.conversion.options.load/vectorizationoptions/enablevectorization) { get; set; } | Active la vectorisation des images. La valeur par défaut est false. |
| [ImageSizeLimit](../../groupdocs.conversion.options.load/vectorizationoptions/imagesizelimit) { get; set; } | Obtient ou définit la dimension maximale de l'image déterminée par la multiplication de la largeur et de la hauteur de l'image. La taille de l'image sera mise à l'échelle en fonction de cette propriété. La valeur par défaut est 1800000. |
| [LineWidth](../../groupdocs.conversion.options.load/vectorizationoptions/linewidth) { get; set; } | Obtient ou définit la largeur du trait. La valeur de ce paramètre est affectée par l'échelle graphique. La valeur par défaut est 1. |
| [Severity](../../groupdocs.conversion.options.load/vectorizationoptions/severity) { get; set; } | Définit la sévérité du lissage du tracé d'image |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
