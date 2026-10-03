---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de gestion des signets dans WordProcessing"
type: docs
weight: 2930
url: /fr/net/groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
## WordProcessingBookmarksOptions class

Options de gestion des signets dans WordProcessing

```csharp
public class WordProcessingBookmarksOptions : ValueObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordProcessingBookmarksOptions](wordprocessingbookmarksoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BookmarksOutlineLevel](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/bookmarksoutlinelevel) { get; set; } | Spécifie le niveau par défaut dans le plan du document où afficher les signets Word. La valeur par défaut est 0. La plage valide est de 0 à 9. |
| [ExpandedOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/expandedoutlinelevels) { get; set; } | Spécifie le nombre de niveaux du plan du document à afficher développés lors de la visualisation du fichier. La valeur par défaut est 0. La plage valide est de 0 à 9. Notez que cette option ne fonctionnera pas lors de l'enregistrement au format XPS. |
| [HeadingsOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/headingsoutlinelevels) { get; set; } | Spécifie le nombre de niveaux de titres (paragraphes formatés avec les styles Titre) à inclure dans le plan du document. La valeur par défaut est 0. La plage valide est de 0 à 9. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
