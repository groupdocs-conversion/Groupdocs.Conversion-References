---
title: "PersonalStorageDocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Contient les métadonnées du document de stockage personnel"
type: docs
weight: 29
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Contient les métadonnées du document de stockage personnel

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | Le stockage est-il protégé par mot de passe |
|
|  | [getRootFolderName()](#getRootFolderName--) | Nom du dossier racine |
|
|  | [getContentCount()](#getContentCount--) | Obtenir le nombre de contenus dans le dossier racine |
|
|  | [getFolders()](#getFolders--) | Dossiers dans le stockage |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stockage | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Le stockage est-il protégé par mot de passe


**Returns:**
booléen
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Nom du dossier racine


**Returns:**
java.lang.String - Nom du dossier racine

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Obtenir le nombre de contenus dans le dossier racine


**Returns:**
int - nombre de contenus dans le dossier racine

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Dossiers dans le stockage


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Dossiers dans le stockage

