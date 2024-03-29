---
title: MarkupConvertOptions
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Options de conversion vers le type de fichier Markup.
type: docs
weight: 1680
url: /fr/net/groupdocs.conversion.options.convert/markupconvertoptions/
---
## MarkupConvertOptions class

Options de conversion vers le type de fichier Markup.

```csharp
[Obsolete("This class will be removed in Conversion.NET 23.3. Please use WebConvertOptions instead.")]
public class MarkupConvertOptions : WebConvertOptions
```

## Propriétés

| Nom | La description |
| --- | --- |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Si`vrai` la mise en page fixe sera utilisée, par exemple les éléments html en position absolue Par défaut : true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Afficher les bordures de page lors de la conversion en mise en page fixe. La valeur par défaut est True. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Le numéro de page à partir duquel commencer la conversion. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | La liste des index de page à convertir. Doit être spécifié pour convertir des pages spécifiques. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Nombre de pages à convertir à partir de`Numéro de page` . |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Si`vrai` , l'entrée est d'abord convertie en PDF et ensuite au format souhaité |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Options spécifiques au filigrane |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance d'options actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sert de fonction de hachage par défaut. |

### Voir également

* class [WebConvertOptions](../webconvertoptions)
* espace de noms [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
