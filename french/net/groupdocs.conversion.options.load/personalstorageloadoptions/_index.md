---
title: "PersonalStorageLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents de stockage personnel."
type: docs
weight: 2750
url: /fr/net/groupdocs.conversion.options.load/personalstorageloadoptions/
---
## PersonalStorageLoadOptions class

Options de chargement des documents de stockage personnel.

```csharp
public sealed class PersonalStorageLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PersonalStorageLoadOptions](personalstorageloadoptions)() | Initialise une nouvelle instance de la classe [`PersonalStorageLoadOptions`](../personalstorageloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowned) { get; } | Implémente [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) en lecture seule. Défini sur true. Les documents possédés seront convertis. |
| [ConvertOwner](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowner) { get; } | Implémente [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) en lecture seule. Défini sur false. Le propriétaire ne sera pas converti. |
| [Depth](../../groupdocs.conversion.options.load/personalstorageloadoptions/depth) { get; set; } | Implémente [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Valeur par défaut : 3. |
| [Folder](../../groupdocs.conversion.options.load/personalstorageloadoptions/folder) { get; set; } | Dossier à traiter Valeur par défaut est Inbox |
| [Format](../../groupdocs.conversion.options.load/personalstorageloadoptions/format) { get; set; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/personalstorageloadoptions/clone)() | Clone l'instance actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
