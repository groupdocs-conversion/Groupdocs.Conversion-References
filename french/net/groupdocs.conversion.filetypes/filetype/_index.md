---
title: FileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Classe de base du type de fichier
type: docs
weight: 850
url: /fr/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

Classe de base du type de fichier

```csharp
public class FileType : Enumeration
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [FileType](filetype)() | Constructeur de sérialisation |

## Propriétés

| Nom | La description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension de fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Obtient le type de fichier pour l'extension de fichier fournie |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Renvoie le type de fichier pour le nom de fichier spécifié |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Renvoie le type de fichier pour le flux de documents fourni |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Détermine si deux instances d'objet sont égales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sert de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Renvoie toutes les valeurs d'énumération. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Conversion implicite en string |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Type de fichier inconnu |

### Voir également

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* espace de noms [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->