---
title: "TypeDeFichierGestionDeProjet"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les formats de fichiers de projet créés par les logiciels de gestion de projet tels que Microsoft Project, Primavera P6, etc. Un fichier de projet est une collection de tâches, de ressources et de leur planification afin d'obtenir un résultat mesurable sous forme de produit ou de service. Documents de gestion de projet. Inclut les types de fichiers suivants : Mpp./projectmanagementfiletype/mpp Mpt./projectmanagementfiletype/mpt Mpx./projectmanagementfiletype/mpx. En savoir plus sur les formats de gestion de projet ici https//wiki.fileformat.com/projectmanagement."
type: docs
weight: 1220
url: /fr/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Définit les formats de fichiers de projet créés par les logiciels de gestion de projet tels que Microsoft Project, Primavera P6, etc. Un fichier de projet est une collection de tâches, de ressources et de leur planification afin d'obtenir un résultat mesurable sous forme de produit ou de service. Documents de gestion de projet. Inclut les types de fichiers suivants : [`Mpp`](./mpp), [`Mpt`](./mpt), [`Mpx`](./mpx). En savoir plus sur les formats de gestion de projet [ici](https://wiki.fileformat.com/project-management).

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | Constructeur de sérialisation |

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
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implémente [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP est un fichier de données Microsoft Project qui stocke les informations liées à la gestion de projet de manière intégrée. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | Les fichiers de modèle Microsoft Project contiennent des informations de base et une structure ainsi que les paramètres de document pour créer des fichiers .MPP. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange File Format est un format de fichier ASCII pour le transfert d'informations de projet entre Microsoft Project (MSP) et d'autres applications qui prennent en charge le format de fichier MPX telles que Primavera Project Planner, Sciforma et Timerline Precision Estimating. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | Le format de fichier XER est un format de fichier de projet propriétaire utilisé par l'application de planification et de gestion de projet Primavera P6. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/project-management/xer). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
