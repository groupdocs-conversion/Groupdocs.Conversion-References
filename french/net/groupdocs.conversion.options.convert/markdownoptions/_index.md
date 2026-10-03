---
title: "MarkdownOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier markdown."
type: docs
weight: 2010
url: /fr/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

Options de conversion vers le type de fichier markdown.

```csharp
public sealed class MarkdownOptions : ValueObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | Initialise une nouvelle instance de la classe [`MarkdownOptions`](../markdownoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | Exporte les images en base64. La valeur par défaut est true. Ignoré lorsque [`ImageSavingCallback`](./imagesavingcallback) est défini. |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | Rappel invoqué une fois par image lors de l'enregistrement du Markdown. Permet à l'appelant de stocker les images à l'extérieur et de remplacer l'URI intégré dans le document. Prend le pas sur [`ExportImagesAsBase64`](./exportimagesasbase64) lorsqu'il n'est pas nul. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
