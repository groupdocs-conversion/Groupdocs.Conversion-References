---
title: "OlmLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Olm."
type: docs
weight: 2700
url: /fr/net/groupdocs.conversion.options.load/olmloadoptions/
---
## OlmLoadOptions class

Options de chargement des documents Olm.

```csharp
public sealed class OlmLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OlmLoadOptions](olmloadoptions)() | Initialise une nouvelle instance de la classe [`OlmLoadOptions`](../olmloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/olmloadoptions/convertowned) { get; } | Implémente [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) en lecture seule. Défini sur true. Les documents possédés seront convertis. |
| [ConvertOwner](../../groupdocs.conversion.options.load/olmloadoptions/convertowner) { get; } | Implémente [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) en lecture seule. Défini sur false. Le propriétaire ne sera pas converti. |
| [Depth](../../groupdocs.conversion.options.load/olmloadoptions/depth) { get; set; } | Implémente [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Valeur par défaut : 3. |
| [Folder](../../groupdocs.conversion.options.load/olmloadoptions/folder) { get; set; } | Dossier à traiter Valeur par défaut est Inbox |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/olmloadoptions/clone)() | Clone l'instance actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
