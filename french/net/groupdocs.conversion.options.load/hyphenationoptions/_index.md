---
title: "HyphenationOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de configuration de la césure des documents."
type: docs
weight: 2570
url: /fr/net/groupdocs.conversion.options.load/hyphenationoptions/
---
## HyphenationOptions class

Options de configuration de la césure des documents.

```csharp
public sealed class HyphenationOptions : ValueObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HyphenationOptions](hyphenationoptions)() | Crée une nouvelle instance de la classe [`HyphenationOptions`](../hyphenationoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoHyphenation](../../groupdocs.conversion.options.load/hyphenationoptions/autohyphenation) { get; set; } | Obtient ou définit la valeur déterminant si la césure automatique est activée pour le document. La valeur par défaut de cette propriété est false. |
| [HyphenateCaps](../../groupdocs.conversion.options.load/hyphenationoptions/hyphenatecaps) { get; set; } | Obtient ou définit la valeur déterminant si les mots écrits en majuscules sont césurés. La valeur par défaut de cette propriété est true. |
| [HyphenationDictionaries](../../groupdocs.conversion.options.load/hyphenationoptions/hyphenationdictionaries) { get; set; } | Dictionnaire contenant les correspondances entre les codes de langue ISO et les flux de dictionnaire de césure fournis. |

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
