---
title: "PageDescriptionLanguageConvertOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier de langage de descriptions de page."
type: docs
weight: 2030
url: /fr/net/groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/
---
## PageDescriptionLanguageConvertOptions class

Options de conversion vers le type de fichier de langage de descriptions de page.

```csharp
public class PageDescriptionLanguageConvertOptions : 
    CommonConvertOptions<PageDescriptionLanguageFileType>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PageDescriptionLanguageConvertOptions](pagedescriptionlanguageconvertoptions)() | Initialise une nouvelle instance de [`PageDescriptionLanguageConvertOptions`](../pagedescriptionlanguageconvertoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implémente [`Format`](../iconvertoptions/format) |
| [Height](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/height) { get; set; } | Hauteur de page souhaitée après conversion, en pixels indépendants du dispositif de 1/96 pouce chacun. Laisser à 0 pour permettre à la cible de conserver la hauteur de page qu'elle déduit elle‑même. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implémente [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implémente [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implémente [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implémente [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Width](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/width) { get; set; } | Largeur de page souhaitée après conversion, en pixels indépendants du dispositif de 1/96 pouce chacun. Laisser à 0 pour permettre à la cible de conserver la largeur de page qu'elle déduit elle‑même. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance actuelle des options. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PageDescriptionLanguageFileType](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
