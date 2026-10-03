---
title: "PersonalStorageDocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "व्यक्तिगत स्टोरेज दस्तावेज़ मेटाडेटा शामिल है"
type: docs
weight: 29
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

व्यक्तिगत स्टोरेज दस्तावेज़ मेटाडेटा शामिल है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | क्या स्टोरेज पासवर्ड से सुरक्षित है |
|
|  | [getRootFolderName()](#getRootFolderName--) | रूट फ़ोल्डर का नाम |
|
|  | [getContentCount()](#getContentCount--) | रूट फ़ोल्डर में सामग्री की गिनती प्राप्त करें |
|
|  | [getFolders()](#getFolders--) | स्टोरेज में फ़ोल्डर |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्टोरेज | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| आकार | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


क्या स्टोरेज पासवर्ड से सुरक्षित है


**Returns:**
बूलियन
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


रूट फ़ोल्डर का नाम


**Returns:**
java.lang.String - रूट फ़ोल्डर का नाम

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


रूट फ़ोल्डर में सामग्री की गिनती प्राप्त करें


**Returns:**
int - रूट फ़ोल्डर में सामग्री की गिनती

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


स्टोरेज में फ़ोल्डर


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - स्टोरेज में फ़ोल्डर

