---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les documents de base de données. Inclut les types de fichiers suivants Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql"
type: docs
weight: 1090
url: /fr/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

Définit les documents de base de données. Inclut les types de fichiers suivants : [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | Constructeur de sérialisation |

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
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | Un fichier avec l'extension .log contient une liste de texte brut avec horodatage. Généralement, certains détails d'activité sont enregistrés par les logiciels ou systèmes d'exploitation pour aider les développeurs ou les utilisateurs à suivre ce qui se passait à un moment donné. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/database/log). |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | Un fichier avec l'extension .nsf (Notes Storage Facility) est un format de fichier de base de données utilisé par le logiciel IBM Notes, auparavant connu sous le nom de Lotus Notes. Il définit le schéma pour stocker différents types d'objets tels que les e‑mails, les rendez‑vous, les documents, les formulaires et les vues. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/database/nsf). |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | Un fichier avec l'extension .sql est un fichier Structured Query Language (SQL) qui contient du code pour travailler avec des bases de données relationnelles. Il est utilisé pour écrire des instructions SQL pour les opérations CRUD (Create, Read, Update, Delete) sur les bases de données. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/database/sql). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
