---
title: "PersonalStorageDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Contiene i metadati del documento di archiviazione personale"
type: docs
weight: 29
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Contiene i metadati del documento di archiviazione personale

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | Lo storage è protetto da password |
|
|  | [getRootFolderName()](#getRootFolderName--) | Nome della cartella radice |
|
|  | [getContentCount()](#getContentCount--) | Ottieni il conteggio dei contenuti nella cartella radice |
|
|  | [getFolders()](#getFolders--) | Cartelle nello storage |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| storage | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| dimensione | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Lo storage è protetto da password


**Returns:**
booleano
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Nome della cartella radice


**Returns:**
java.lang.String - Nome della cartella radice

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Ottieni il conteggio dei contenuti nella cartella radice


**Returns:**
int - conteggio dei contenuti nella cartella radice

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Cartelle nello storage


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Cartelle nello storage

