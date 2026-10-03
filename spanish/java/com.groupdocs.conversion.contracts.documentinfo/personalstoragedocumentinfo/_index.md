---
title: "PersonalStorageDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Contiene metadatos del documento de almacenamiento personal"
type: docs
weight: 29
url: /es/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento de almacenamiento personal

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | ¿Está el almacenamiento protegido con contraseña? |
|
|  | [getRootFolderName()](#getRootFolderName--) | Nombre de la carpeta raíz |
|
|  | [getContentCount()](#getContentCount--) | Obtener recuento de contenidos en la carpeta raíz |
|
|  | [getFolders()](#getFolders--) | Carpetas en el almacenamiento |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| almacenamiento | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


¿Está el almacenamiento protegido con contraseña?


**Returns:**
booleano
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Nombre de la carpeta raíz


**Returns:**
java.lang.String - Nombre de la carpeta raíz

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Obtener recuento de contenidos en la carpeta raíz


**Returns:**
int - recuento de contenidos en la carpeta raíz

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Carpetas en el almacenamiento


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Carpetas en el almacenamiento

