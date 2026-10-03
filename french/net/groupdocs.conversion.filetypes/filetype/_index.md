---
title: "FileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Classe de base du type de fichier"
type: docs
weight: 1130
url: /fr/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

Classe de base du type de fichier

```csharp
public class FileType : Enumeration
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FileType](filetype)() | Constructeur de sérialisation |

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension du fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Obtient FileType pour le fileExtension fourni |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Renvoie FileType pour le fileName spécifié |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Renvoie FileType pour le flux de document fourni |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | Implémente [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Renvoie toutes les valeurs d'énumération. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Conversion implicite en chaîne |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Type de fichier inconnu |

### Voir aussi

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
