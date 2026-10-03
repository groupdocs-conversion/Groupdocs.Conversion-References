---
title: "RasterImageLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Image."
type: docs
weight: 2800
url: /fr/net/groupdocs.conversion.options.load/rasterimageloadoptions/
---
## RasterImageLoadOptions class

Options de chargement des documents Image.

```csharp
public sealed class RasterImageLoadOptions : BaseImageLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RasterImageLoadOptions](rasterimageloadoptions)() | Initialise une nouvelle instance de la classe [`RasterImageLoadOptions`](../rasterimageloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [CropArea](../../groupdocs.conversion.options.load/rasterimageloadoptions/croparea) { get; set; } | Recadrer la zone d'image avant la conversion |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Police par défaut pour les types de documents Psd, Emf, Wmf. La police suivante sera utilisée si une police est manquante. |
| [Format](../../groupdocs.conversion.options.load/rasterimageloadoptions/format) { get; set; } | Type de fichier du document d'entrée. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | Réinitialise les dossiers de polices avant de charger le document |
| [VectorizationOptions](../../groupdocs.conversion.options.load/rasterimageloadoptions/vectorizationoptions) { get; set; } | Définit les options de vectorisation |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |
| [SetHeicConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setheicconnector)(IHeicConnector) | Définit le connecteur d'image Heic |
| [SetOcrConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setocrconnector)(IOcrConnector) | Définit le connecteur OCR d'image |

### Voir aussi

* class [BaseImageLoadOptions](../baseimageloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
