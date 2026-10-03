---
title: "WatermarkImageOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options pour définir le filigrane du document converti"
type: docs
weight: 2290
url: /fr/net/groupdocs.conversion.options.convert/watermarkimageoptions/
---
## WatermarkImageOptions class

Options pour définir le filigrane du document converti

```csharp
public sealed class WatermarkImageOptions : WatermarkOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WatermarkImageOptions](watermarkimageoptions)(byte[]) | Créer la classe WatermarkOptions et définir le texte du filigrane |

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Redimensionner automatiquement le filigrane. Si la valeur est vraie, la position et la taille sont calculées automatiquement pour s'adapter à la taille de la page. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Indique que le filigrane est appliqué en arrière-plan. Si la valeur est vraie, le filigrane est placé en bas. Par défaut, c'est faux et le filigrane est placé au premier plan. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Hauteur du filigrane |
| [Image](../../groupdocs.conversion.options.convert/watermarkimageoptions/image) { get; } | Filigrane d'image |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Position gauche du filigrane |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Angle de rotation du filigrane |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Position supérieure du filigrane |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Transparence du filigrane. Valeur entre 0 et 1. La valeur 0 est entièrement visible, la valeur 1 est invisible. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Largeur du filigrane |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Cloner l'instance actuelle |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [WatermarkOptions](../watermarkoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
