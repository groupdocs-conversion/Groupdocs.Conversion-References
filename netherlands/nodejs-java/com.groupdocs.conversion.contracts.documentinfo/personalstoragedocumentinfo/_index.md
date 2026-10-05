---
title: "PersonalStorageDocumentInfo"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Bevat persoonlijke opslag-documentmetadata"
type: docs
weight: 32
url: /nl/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Bevat persoonlijke opslag-documentmetadata
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isPasswordProtected()](#isPasswordProtected--) | Is opslag met wachtwoord beveiligd |
| [getRootFolderName()](#getRootFolderName--) | Naam van hoofdmap |
| [getContentCount()](#getContentCount--) | Haal het aantal items op in de hoofdmap |
| [getFolders()](#getFolders--) | Mappen in de opslag |
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| opslag | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Is opslag met wachtwoord beveiligd

**Returns:**
boolean
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Naam van hoofdmap

**Returns:**
java.lang.String - Naam van hoofdmap
### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Haal het aantal items op in de hoofdmap

**Returns:**
int - aantal items in de hoofdmap
### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Mappen in de opslag

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Mappen in de opslag
