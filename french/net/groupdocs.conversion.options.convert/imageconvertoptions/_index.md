---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier Image."
type: docs
weight: 1950
url: /fr/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Options de conversion vers le type de fichier Image.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Initialise une nouvelle instance de la classe [`ImageConvertOptions`](../imageconvertoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Définit la couleur d'arrière-plan lorsque le format source le prend en charge |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Ajuste la luminosité de l'image. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | Lorsqu'il est activé, il limite la résolution de rendu PDF par page à la résolution raster native de la page afin qu'aucune page ne soit rendue à un DPI supérieur à celui de l'image intégrée, et émet cette page avec ses dimensions de pixel natives (plus petites) et son DPI natif dans la sortie finale au lieu de la ré‑inflater au DPI demandé. Seules les pages dominées par des images (numérisations) sont concernées ; les pages contenant du texte ou du contenu vectoriel ne sont jamais adoucies et sont émises au DPI demandé. Ignoré lorsqu'une sortie explicite [`Width`](./width) ou [`Height`](./height) est définie. La valeur par défaut est `false` (pas de limitation ; chaque page est rendue et émise au DPI demandé). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Ajuste le contraste de l'image. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Recadre la zone de l'image raster après conversion |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Mode de retournement d'image. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implémente [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Ajuste le gamma de l'image. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Indique s'il faut convertir en image en niveaux de gris. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Hauteur d'image souhaitée après conversion. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Résolution horizontale d'image souhaitée après conversion. La résolution par défaut est celle du fichier d'entrée ou 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Options de conversion spécifiques à Jpeg. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Limite inférieure par axe appliquée au DPI de rendu limité lorsque [`CapResolutionToPageContent`](./capresolutiontopagecontent) est activé. Le DPI limité n'est jamais réduit en dessous de cette valeur. La valeur par défaut est `0` (pas de plancher). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implémente [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implémente [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implémente [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Options de conversion spécifiques à Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Angle de rotation de l'image. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Options de conversion spécifiques à Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Si `true`, l'entrée est d'abord convertie en PDF puis ensuite au format souhaité. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Résolution verticale souhaitée de l'image après conversion. La résolution par défaut est celle du fichier d'entrée ou 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implémente [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Options de conversion spécifiques à Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Largeur d'image souhaitée après conversion. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance actuelle des options. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
