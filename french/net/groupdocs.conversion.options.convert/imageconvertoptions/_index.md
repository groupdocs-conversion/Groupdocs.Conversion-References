---
title: ImageConvertOptions
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Options de conversion en type de fichier image.
type: docs
weight: 1630
url: /fr/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Options de conversion en type de fichier image.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Initialise la nouvelle instance de[`ImageConvertOptions`](../imageconvertoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Définit la couleur d'arrière-plan lorsqu'elle est prise en charge par le format source |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Ajuste la luminosité de l'image. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Ajuste le contraste de l'image. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Mode retournement d'image. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Ajuste le gamma de l'image. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Indique s'il faut convertir en image en niveaux de gris. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Hauteur d'image souhaitée après conversion. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Résolution horizontale de l'image souhaitée après conversion. La résolution par défaut est la résolution du fichier d'entrée soit 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Options de conversion spécifiques à Jpeg. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Le numéro de page à partir duquel commencer la conversion. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | La liste des index de page à convertir. Doit être spécifié pour convertir des pages spécifiques. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Nombre de pages à convertir à partir de`Numéro de page` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Options de conversion spécifiques à Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Angle de rotation de l'image. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Options de conversion spécifiques à Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Si`vrai` , l'entrée est d'abord convertie en PDF et ensuite au format souhaité. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Résolution verticale de l'image souhaitée après conversion. La résolution par défaut est la résolution du fichier d'entrée soit 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Options spécifiques au filigrane |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Options de conversion spécifiques à Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Largeur d'image souhaitée après conversion. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance d'options actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sert de fonction de hachage par défaut. |

### Voir également

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* espace de noms [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
