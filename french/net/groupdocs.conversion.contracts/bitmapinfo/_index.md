---
title: "BitmapInfo"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Objet contenant un tableau de pixels et des informations bitmap."
type: docs
weight: 70
url: /fr/net/groupdocs.conversion.contracts/bitmapinfo/
---
## BitmapInfo class

Objet contenant un tableau de pixels et des informations bitmap.

```csharp
public class BitmapInfo : ValueObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.conversion.contracts/bitmapinfo/format) { get; } | Obtient le format de pixel du bitmap. |
| [Height](../../groupdocs.conversion.contracts/bitmapinfo/height) { get; } | Obtient la hauteur du bitmap. |
| [PixelBytes](../../groupdocs.conversion.contracts/bitmapinfo/pixelbytes) { get; } | Obtient le tableau de pixels. |
| [Width](../../groupdocs.conversion.contracts/bitmapinfo/width) { get; } | Obtient la largeur du bitmap. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/bitmapinfo/create)(byte[], int, int, PixelFormat) | Créer une nouvelle instance de BitmapInfo |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

## Autres membres

| Nom | Description |
| --- | --- |
| class [PixelFormat](bitmapinfo.pixelformat) | Décrit l'énumération du format de pixel |

### Voir aussi

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
