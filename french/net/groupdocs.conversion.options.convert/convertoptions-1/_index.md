---
title: ConvertOptionsTFileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Classe doptions de conversion générique abstraite.
type: docs
weight: 1470
url: /fr/net/groupdocs.conversion.options.convert/convertoptions-1/
---
## ConvertOptions&lt;TFileType&gt; class

Classe d'options de conversion générique abstraite.

```csharp
public abstract class ConvertOptions<TFileType> : ConvertOptions
    where TFileType : FileType
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance d'options actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sert de fonction de hachage par défaut. |

### Voir également

* class [ConvertOptions](../convertoptions)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* espace de noms [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
