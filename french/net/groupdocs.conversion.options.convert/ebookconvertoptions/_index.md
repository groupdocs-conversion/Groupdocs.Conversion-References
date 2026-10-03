---
title: "EBookConvertOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier EBook."
type: docs
weight: 1790
url: /fr/net/groupdocs.conversion.options.convert/ebookconvertoptions/
---
## EBookConvertOptions class

Options de conversion vers le type de fichier EBook.

```csharp
public class EBookConvertOptions : CommonConvertOptions<EBookFileType>, IPageOrientationOptions, 
    IPageSizeOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EBookConvertOptions](ebookconvertoptions)() | Initialise une nouvelle instance de la classe [`EBookConvertOptions`](../ebookconvertoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/ebookconvertoptions/fallbackpagesize) { get; set; } | Taille de page de secours |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implémente [`Format`](../iconvertoptions/format) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/orientationsettings) { get; set; } | Paramètres d'orientation de page |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implémente [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implémente [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implémente [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SizeSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/sizesettings) { get; set; } | Paramètres de taille de page |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implémente [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance actuelle des options. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [EBookFileType](../../groupdocs.conversion.filetypes/ebookfiletype)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
