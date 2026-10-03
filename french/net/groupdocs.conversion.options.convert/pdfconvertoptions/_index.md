---
title: "PdfConvertOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier Pdf."
type: docs
weight: 2060
url: /fr/net/groupdocs.conversion.options.convert/pdfconvertoptions/
---
## PdfConvertOptions class

Options de conversion vers le type de fichier Pdf.

```csharp
public class PdfConvertOptions : CommonConvertOptions<PdfFileType>, IDpiConvertOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IPasswordConvertOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfConvertOptions](pdfconvertoptions)() | Initialise une nouvelle instance de la classe [`PdfConvertOptions`](../pdfconvertoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/pdfconvertoptions/dpi) { get; set; } | DPI de page souhaité après conversion. La résolution par défaut est : 96 dpi. |
| [EmbedFullFonts](../../groupdocs.conversion.options.convert/pdfconvertoptions/embedfullfonts) { get; set; } | Lorsqu'il est défini sur true, le fichier de police complet est intégré dans le PDF au lieu d'un sous-ensemble. Cela augmente la taille du fichier de sortie mais garantit une meilleure compatibilité lors de l'édition du PDF résultant. S'applique uniquement lors de la conversion à partir de documents WordProcessing. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/pdfconvertoptions/fallbackpagesize) { get; set; } | Taille de page de secours |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implémente [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginsettings) { get; set; } | Paramètres des marges de page |
| [OrientationSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/orientationsettings) { get; set; } | Paramètres d'orientation de page |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implémente [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implémente [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implémente [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/pdfconvertoptions/password) { get; set; } | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
| [PdfOptions](../../groupdocs.conversion.options.convert/pdfconvertoptions/pdfoptions) { get; set; } | Options de conversion spécifiques au PDF |
| [ResizeMode](../../groupdocs.conversion.options.convert/pdfconvertoptions/resizemode) { get; set; } | Spécifie comment le contenu doit être redimensionné lorsque la taille de la page est modifiée. La valeur par défaut est AlignTopLeft (pas de mise à l'échelle). |
| [Rotate](../../groupdocs.conversion.options.convert/pdfconvertoptions/rotate) { get; set; } | Rotation de page |
| [SizeSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/sizesettings) { get; set; } | Paramètres de taille de page |
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
* class [PdfFileType](../../groupdocs.conversion.filetypes/pdffiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
