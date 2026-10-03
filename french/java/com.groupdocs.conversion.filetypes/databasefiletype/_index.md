---
title: "DatabaseFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents CAD (Conception Assistée par Ordinateur) qui sont utilisés pour des formats de fichiers graphiques 3D et peuvent contenir des conceptions 2D ou 3D."
type: docs
weight: 12
url: /fr/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Définit les documents CAD (Conception Assistée par Ordinateur) qui sont utilisés pour les formats de fichiers graphiques 3D et peuvent contenir des conceptions 2D ou 3D.
Inclut les types suivants :
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
En savoir plus sur les formats CAD [ici](../https://wiki.fileformat.com/cad).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Nsf](#Nsf) | Un fichier avec l'extension .nsf (Notes Storage Facility) est un format de fichier de base de données utilisé par le logiciel IBM Notes, auparavant connu sous le nom de Lotus Notes. |
|
|  | [Log](#Log) | Un fichier avec l'extension .log contient une liste de texte brut avec horodatage. |
|
|  | [Sql](#Sql) | Un fichier avec l'extension .sql est un fichier Structured Query Language (SQL) contenant du code pour travailler avec des bases de données relationnelles. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Constructeur de sérialisation


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


Un fichier avec l'extension .nsf (Notes Storage Facility) est un format de fichier de base de données utilisé par le logiciel IBM Notes, auparavant connu sous le nom de Lotus Notes. Il définit le schéma permettant de stocker différents types d'objets tels que les courriels, les rendez-vous, les documents, les formulaires et les vues. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/database/nsf).


### Log {#Log}
```
public static final DatabaseFileType Log
```


Un fichier avec l'extension .log contient une liste de texte brut avec horodatage. Généralement, certains détails d'activité sont enregistrés par les logiciels ou les systèmes d'exploitation afin d'aider les développeurs ou les utilisateurs à suivre ce qui se passait pendant une période donnée. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/database/log).


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


Un fichier avec l'extension .sql est un fichier Structured Query Language (SQL) contenant du code pour travailler avec des bases de données relationnelles. Il est utilisé pour écrire des instructions SQL pour les opérations CRUD (Create, Read, Update, and Delete) sur les bases de données. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/database/sql).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement par défaut préparées pour le type de fichier source


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
