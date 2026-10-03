---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les options d'optimisation PDF."
type: docs
weight: 2120
url: /fr/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Définit les options d'optimisation PDF.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Initialise une nouvelle instance de la classe [`PdfOptimizationOptions`](../pdfoptimizationoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Si CompressImages est réglé sur `true`, toutes les images du document sont recompressées. La compression est définie par la propriété ImageQuality. |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | Définir la stratégie de sous-ensemble de polices |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Valeur en pourcentage où 100 % correspond à une qualité et une taille d'image inchangées. Pour réduire la taille de l'image, définissez cette propriété à moins de 100 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Lier les flux dupliqués |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Supprimer les objets inutilisés |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Supprimer les flux inutilisés |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | Ne pas incorporer les polices si réglé sur true |

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
