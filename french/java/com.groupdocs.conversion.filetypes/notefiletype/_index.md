---
title: "NoteFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les formats de prise de notes."
type: docs
weight: 19
url: /fr/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Définit les formats de prise de notes. Inclut les types de fichiers suivants :
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
En savoir plus sur les formats de prise de notes [ici](../https://wiki.fileformat.com/note-taking).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [One](#One) | Les fichiers représentés par l'extension .ONE sont créés par l'application Microsoft OneNote. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Constructeur de sérialisation


### One {#One}
```
public static final NoteFileType One
```


Les fichiers représentés par l'extension .ONE sont créés par l'application Microsoft OneNote. OneNote vous permet de rassembler des informations en utilisant l'application comme si vous utilisiez votre carnet de brouillon pour prendre des notes.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/note-taking/one).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement par défaut préparées pour le type de fichier source


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
