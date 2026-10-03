---
title: "PdfOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier Pdf."
type: docs
weight: 2130
url: /fr/net/groupdocs.conversion.options.convert/pdfoptions/
---
## PdfOptions class

Options de conversion vers le type de fichier Pdf.

```csharp
public sealed class PdfOptions : ValueObject, IZoomConvertOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfOptions](pdfoptions)() | Initialise une nouvelle instance de la classe [`PdfOptions`](../pdfoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [DocumentInfo](../../groupdocs.conversion.options.convert/pdfoptions/documentinfo) { get; set; } | Métadonnées du document PDF. |
| [FormattingOptions](../../groupdocs.conversion.options.convert/pdfoptions/formattingoptions) { get; set; } | Options de formatage PDF |
| [Grayscale](../../groupdocs.conversion.options.convert/pdfoptions/grayscale) { get; set; } | Convertir un PDF de l’espace colorimétrique RVB en niveaux de gris |
| [Linearize](../../groupdocs.conversion.options.convert/pdfoptions/linearize) { get; set; } | Linéarise le document PDF pour le Web |
| [OptimizationOptions](../../groupdocs.conversion.options.convert/pdfoptions/optimizationoptions) { get; set; } | Options d’optimisation PDF |
| [PdfFormat](../../groupdocs.conversion.options.convert/pdfoptions/pdfformat) { get; set; } | Définit le format PDF du document converti. |
| [RemovePdfACompliance](../../groupdocs.conversion.options.convert/pdfoptions/removepdfacompliance) { get; set; } | Supprime la conformité PDF/A |
| [Zoom](../../groupdocs.conversion.options.convert/pdfoptions/zoom) { get; set; } | Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
