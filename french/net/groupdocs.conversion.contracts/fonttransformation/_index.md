---
title: "FontTransformation"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Décrit la configuration de transformation des polices, y compris les attributs de police. Les transformations de police sont appliquées après le chargement du document et la substitution de police."
type: docs
weight: 260
url: /fr/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

Décrit la configuration de transformation des polices, y compris les attributs de police. Les transformations de police sont appliquées après le chargement du document et la substitution de police.

```csharp
public class FontTransformation : ValueObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | Lorsque vrai, correspond à n'importe quelle taille de police pour le nom de police d'origine. Lorsque faux, correspond à la taille de police exacte spécifiée dans OriginalFont. |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | Lorsque vrai, correspond à n'importe quel style de police (gras, italique, souligné) pour la police d'origine. Lorsque faux, correspond au style de police exact spécifié dans OriginalFont. |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | La spécification de police d'origine à correspondre et à remplacer. |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | La spécification de police de remplacement. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | Crée une transformation de police avec une correspondance exacte de police (la taille et le style doivent correspondre). |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | Crée une transformation de police uniquement par le nom, en correspondant à n'importe quelle taille et style. La police de remplacement préservera la taille et le style de la police d'origine. |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | Crée une transformation de police avec des options de correspondance flexibles. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
