---
title: "FontSubstitutionContext"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Décrit une substitution de police unique qui s'est produite lors du chargement ou du rendu d'un document source. Les instances sont transmises à OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted."
type: docs
weight: 250
url: /fr/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

Décrit une substitution de police unique qui s'est produite lors du chargement ou du rendu d'un document source. Les instances sont transmises à [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted).

```csharp
public sealed class FontSubstitutionContext
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | Crée un nouveau [`FontSubstitutionContext`](../fontsubstitutioncontext). |

## Propriétés

| Nom | Description |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | Nom de la police référencée par le document source mais indisponible pour le pipeline de conversion. |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | Le message de substitution exactement tel que rapporté par le pipeline de conversion, mot à mot et non analysé. Pour les documents qui exposent les noms de police de manière structurée, cela peut être `null` (utilisez [`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname)) ; pour les autres, il contient la description lisible complète, qui indique à la fois la police manquante et la police de substitution. |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | Nom de fichier du document source en cours de conversion. Lorsque la source a été fournie sous forme de flux qui n’est pas un FileStream, cela contient un identifiant généré plutôt qu’un vrai nom de fichier. |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | Nom de la police utilisée comme substitution. Peut être `null` pour les documents dont le moteur signale la substitution uniquement sous forme de texte descriptif — dans ce cas, lisez [`Reason`](./reason). |

### Voir aussi

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
