---
title: "PersonalStorageDocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Enthält Metadaten für persönliche Speicher-Dokumente"
type: docs
weight: 29
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Enthält Metadaten für persönliche Speicher-Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | Ist der Speicher passwortgeschützt |
|
|  | [getRootFolderName()](#getRootFolderName--) | Name des Stammordners |
|
|  | [getContentCount()](#getContentCount--) | Anzahl der Inhalte im Stammordner abrufen |
|
|  | [getFolders()](#getFolders--) | Ordner im Speicher |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Speicher | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| Größe | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Ist der Speicher passwortgeschützt


**Returns:**
boolean
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Name des Stammordners


**Returns:**
java.lang.String - Name des Stammordners

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Anzahl der Inhalte im Stammordner abrufen


**Returns:**
int - Anzahl der Inhalte im Stammordner

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Ordner im Speicher


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Ordner im Speicher

