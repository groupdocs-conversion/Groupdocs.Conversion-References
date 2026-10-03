---
title: "PersonalStorageDocumentInfo"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Innehåller metadata för personligt lagringsdokument"
type: docs
weight: 29
url: /sv/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Innehåller metadata för personligt lagringsdokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | Är lagring lösenordsskyddad |
|
|  | [getRootFolderName()](#getRootFolderName--) | Rotmappens namn |
|
|  | [getContentCount()](#getContentCount--) | Hämta antalet innehåll i rotmappen |
|
|  | [getFolders()](#getFolders--) | Mappar i lagringen |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lagring | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| storlek | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Är lagring lösenordsskyddad


**Returns:**
boolean
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Rotmappens namn


**Returns:**
java.lang.String - Rotmappens namn

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Hämta antalet innehåll i rotmappen


**Returns:**
int - antal innehåll i rotmappen

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Mappar i lagringen


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Mappar i lagringen

