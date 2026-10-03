---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier Web."
type: docs
weight: 2320
url: /fr/net/groupdocs.conversion.options.convert/webconvertoptions/
---
## WebConvertOptions class

Options de conversion vers le type de fichier Web.

```csharp
public class WebConvertOptions : CommonConvertOptions<WebFileType>, IUsePdfConvertOptions, 
    IZoomConvertOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WebConvertOptions](webconvertoptions)() | Initialise une nouvelle instance de la classe [`WebConvertOptions`](../webconvertoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [EmbedFontResources](../../groupdocs.conversion.options.convert/webconvertoptions/embedfontresources) { get; set; } | Spécifie si les ressources de police doivent être intégrées dans le HTML principal. La valeur par défaut est false. Remarque : si FixedLayout est défini sur true, les ressources de police seront toujours intégrées. |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Si `true`, la mise en page fixe sera utilisée, par ex. les éléments HTML positionnés absolument. Valeur par défaut : true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Afficher les bordures de page lors de la conversion en mise en page fixe. La valeur par défaut est True. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implémente [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implémente [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implémente [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implémente [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SlideShow](../../groupdocs.conversion.options.convert/webconvertoptions/slideshow) { get; set; } | S'applique uniquement à la conversion d'une présentation vers [`Html`](../../groupdocs.conversion.filetypes/webfiletype/html) ou [`Htm`](../../groupdocs.conversion.filetypes/webfiletype/htm), et est ignoré pour toute autre conversion. Spécifie si la présentation devient un diaporama HTML interactif avec des transitions de diapositives et des animations de formes, au lieu de la page HTML statique par défaut. La valeur par défaut est false. |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Si `true`, l'entrée est d'abord convertie en PDF puis ensuite au format souhaité. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implémente [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance actuelle des options. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WebFileType](../../groupdocs.conversion.filetypes/webfiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
