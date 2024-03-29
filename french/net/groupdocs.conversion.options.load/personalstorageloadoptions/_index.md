---
title: PersonalStorageLoadOptions
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Options de chargement des documents de stockage personnels.
type: docs
weight: 2230
url: /fr/net/groupdocs.conversion.options.load/personalstorageloadoptions/
---
## PersonalStorageLoadOptions class

Options de chargement des documents de stockage personnels.

```csharp
public sealed class PersonalStorageLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PersonalStorageLoadOptions](personalstorageloadoptions)() | Initialise la nouvelle instance de[`PersonalStorageLoadOptions`](../personalstorageloadoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowned) { get; } | Option pour contrôler si les documents détenus dans le conteneur de documents doivent être convertis |
| [ConvertOwner](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowner) { get; } | Option pour contrôler si le conteneur de documents lui-même doit être converti Si cette propriété est vraie, le conteneur de documents sera le premier document converti |
| [Depth](../../groupdocs.conversion.options.load/personalstorageloadoptions/depth) { get; set; } | Option pour contrôler le nombre de niveaux en profondeur pour effectuer la conversion |
| [Folder](../../groupdocs.conversion.options.load/personalstorageloadoptions/folder) { get; set; } | Dossier à traiter La valeur par défaut est Inbox |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/personalstorageloadoptions/clone)() | Clone l'instance actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sert de fonction de hachage par défaut. |

### Voir également

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* espace de noms [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
