---
title: WordProcessingConvertOptions
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Options de conversion vers le type de fichier WordProcessing.
type: docs
weight: 1810
url: /fr/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Options de conversion vers le type de fichier WordProcessing.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Initialise la nouvelle instance de[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | DPI de la page souhaitée après conversion. La résolution par défaut est : 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Hauteur de page souhaitée après conversion. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Marge inférieure de la page souhaitée en pixels après conversion. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Marge gauche de la page souhaitée en pixels après conversion. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Marge droite de la page souhaitée en pixels après conversion. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Marge supérieure de la page souhaitée en pixels après conversion. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Le numéro de page à partir duquel commencer la conversion. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Orientation de page souhaitée après conversion |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | La liste des index de page à convertir. Doit être spécifié pour convertir des pages spécifiques. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Nombre de pages à convertir à partir de`Numéro de page` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Taille de page souhaitée après conversion |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Mode de reconnaissance lors de la conversion à partir de pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Options de conversion spécifiques RTF |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Options spécifiques au filigrane |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Largeur de page souhaitée après conversion. |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100. Le zoom par défaut est pris en charge jusqu'à Microsoft Word 2010. À partir de Microsoft Word 2013, le zoom par défaut n'est plus défini sur le document, mais il semble utiliser le facteur de zoom du dernier document ouvert. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance d'options actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sert de fonction de hachage par défaut. |

### Voir également

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* espace de noms [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
