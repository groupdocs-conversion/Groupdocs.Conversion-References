---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier de traitement de texte."
type: docs
weight: 2340
url: /fr/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Options de conversion vers le type de fichier de traitement de texte.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IDpiConvertOptions, IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, 
    IPasswordConvertOptions, IPdfRecognitionModeOptions, IZoomConvertOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Initialise une nouvelle instance de la classe [`WordProcessingConvertOptions`](../wordprocessingconvertoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | DPI de page souhaité après conversion. La résolution par défaut est : 96 dpi. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallbackpagesize) { get; set; } | Taille de page de secours |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implémente [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginsettings) { get; set; } | Paramètres des marges de page |
| [MarkdownOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdownoptions) { get; set; } | Implémente [`MarkdownOptions`](./markdownoptions) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientationsettings) { get; set; } | Paramètres d'orientation de page |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implémente [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implémente [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implémente [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Implémente [`PdfRecognitionMode`](../ipdfrecognitionmodeoptions/pdfrecognitionmode) |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Options de conversion spécifiques au RTF |
| [SizeSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/sizesettings) { get; set; } | Paramètres de taille de page |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implémente [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100. Le zoom par défaut est pris en charge jusqu'à Microsoft Word 2010. À partir de Microsoft Word 2013, le zoom par défaut n'est plus appliqué au document, il semble plutôt utiliser le facteur de zoom du dernier document ouvert. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance actuelle des options. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
