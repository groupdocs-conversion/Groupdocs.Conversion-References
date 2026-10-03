---
title: "PersonalStorageFolderInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "व्यक्तिगत संग्रह फ़ोल्डर जानकारी"
type: docs
weight: 30
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragefolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class PersonalStorageFolderInfo extends ValueObject
```

व्यक्तिगत संग्रह फ़ोल्डर जानकारी

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)](#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [items](#items) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getName()](#getName--) | फ़ोल्डर का नाम |
|
|  | [getItemsCount()](#getItemsCount--) | फ़ोल्डर में आइटमों की गिनती |
|
| [getSubFolders()](#getSubFolders--) |  |
| [getItems()](#getItems--) |  |
|  | [toString()](#toString--) | व्यक्तिगत संग्रह फ़ोल्डर जानकारी का स्ट्रिंग प्रतिनिधित्व |
|
### PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items) {#PersonalStorageFolderInfo-java.lang.String-java.util.List-com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo--}
```
public PersonalStorageFolderInfo(String name, List<PersonalStorageItemInfo> items)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |
| आइटम | java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo> |  |

### items {#items}
```
public List<PersonalStorageItemInfo> items
```


### getName() {#getName--}
```
public String getName()
```


फ़ोल्डर का नाम


**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


फ़ोल्डर में आइटमों की गिनती


**Returns:**
int
### getSubFolders() {#getSubFolders--}
```
public List<PersonalStorageFolderInfo> getSubFolders()
```




**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo>
### getItems() {#getItems--}
```
public List<PersonalStorageItemInfo> getItems()
```




**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageItemInfo>
### toString() {#toString--}
```
public String toString()
```


व्यक्तिगत संग्रह फ़ोल्डर जानकारी का स्ट्रिंग प्रतिनिधित्व


**Returns:**
java.lang.String - व्यक्तिगत संग्रह फ़ोल्डर जानकारी का स्ट्रिंग प्रतिनिधित्व फ़ॉर्मेट FolderName (ItemsCount) में

