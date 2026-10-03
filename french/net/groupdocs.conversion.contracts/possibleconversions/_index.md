---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Représente une correspondance des paires de conversion prises en charge pour un format de fichier source spécifique"
type: docs
weight: 510
url: /fr/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Représente une correspondance des paires de conversion prises en charge pour un format de fichier source spécifique

```csharp
public sealed class PossibleConversions : ValueObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Tous les types de fichiers cibles et le drapeau primaire/secondaire IEnumerable de [`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Renvoie la conversion cible pour le type de fichier cible spécifié (2 indexeurs) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Options de chargement prédéfinies pouvant être utilisées pour convertir depuis le type actuel |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Types de fichiers cibles primaires |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Types de fichiers cibles secondaires |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Formats de fichiers source |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
