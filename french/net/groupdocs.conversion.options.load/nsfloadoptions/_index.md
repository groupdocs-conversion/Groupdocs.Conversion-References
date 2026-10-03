---
title: "NsfLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Nsf."
type: docs
weight: 2690
url: /fr/net/groupdocs.conversion.options.load/nsfloadoptions/
---
## NsfLoadOptions class

Options de chargement des documents Nsf.

```csharp
public sealed class NsfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [NsfLoadOptions](nsfloadoptions)() | Initialise une nouvelle instance de la classe [`NsfLoadOptions`](../nsfloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/nsfloadoptions/convertowned) { get; } | Implémente [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) en lecture seule. Défini sur true. Les documents possédés seront convertis. |
| [ConvertOwner](../../groupdocs.conversion.options.load/nsfloadoptions/convertowner) { get; } | Implémente [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) en lecture seule. Défini sur false. Le propriétaire ne sera pas converti. |
| [Depth](../../groupdocs.conversion.options.load/nsfloadoptions/depth) { get; set; } | Implémente [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Valeur par défaut : 3. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/nsfloadoptions/clone)() | Clone l'instance actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
