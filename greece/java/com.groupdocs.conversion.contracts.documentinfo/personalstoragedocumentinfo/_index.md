---
title: "PersonalStorageDocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιέχει μεταδεδομένα εγγράφου προσωπικής αποθήκευσης"
type: docs
weight: 29
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Περιέχει μεταδεδομένα εγγράφου προσωπικής αποθήκευσης

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | Η αποθήκευση είναι προστατευμένη με κωδικό |
|
|  | [getRootFolderName()](#getRootFolderName--) | Όνομα ριζικού φακέλου |
|
|  | [getContentCount()](#getContentCount--) | Λάβετε τον αριθμό των περιεχομένων του ριζικού φακέλου |
|
|  | [getFolders()](#getFolders--) | Φάκελοι στην αποθήκευση |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| αποθήκευση | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| μέγεθος | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Η αποθήκευση είναι προστατευμένη με κωδικό


**Returns:**
boolean
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Όνομα ριζικού φακέλου


**Returns:**
java.lang.String - Όνομα ριζικού φακέλου

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Λάβετε τον αριθμό των περιεχομένων του ριζικού φακέλου


**Returns:**
int - αριθμός περιεχομένων του ριζικού φακέλου

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Φάκελοι στην αποθήκευση


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Φάκελοι στην αποθήκευση

