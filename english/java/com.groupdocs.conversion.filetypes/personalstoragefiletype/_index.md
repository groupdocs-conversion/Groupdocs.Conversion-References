---
title: PersonalStorageFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Personal storage file formats that are used by email applications to store their various data including email messages attachments folders address books etc.
type: docs
weight: 20
url: /java/com.groupdocs.conversion.filetypes/personalstoragefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public class PersonalStorageFileType extends FileType implements Serializable
```

Defines Personal storage file formats that are used by email applications to store their various data including email messages, attachments, folders, address books etc. Includes the following file types: , , Learn more about Email formats [here][].


[here]: https://wiki.fileformat.com/email
## Constructors

| Constructor | Description |
| --- | --- |
| [PersonalStorageFileType()](#PersonalStorageFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Pst](#Pst) | Files with .PST extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. |
| [Ost](#Ost) | OST or Offline Storage Files represent user's mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. |
| [Nsf](#Nsf) | A file with .nsf (Notes Storage Facility) extension is a database file format used by the IBM Notes software, which was previously known as Lotus Notes. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### PersonalStorageFileType() {#PersonalStorageFileType--}
```
public PersonalStorageFileType()
```


Serialization constructor

### Pst {#Pst}
```
public static final PersonalStorageFileType Pst
```


Files with .PST extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/pst

### Ost {#Ost}
```
public static final PersonalStorageFileType Ost
```


OST or Offline Storage Files represent user's mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/ost

### Nsf {#Nsf}
```
public static final PersonalStorageFileType Nsf
```


A file with .nsf (Notes Storage Facility) extension is a database file format used by the IBM Notes software, which was previously known as Lotus Notes. It defines the schema to store different kind of objects such like emails, appointments, documents, forms and views. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/database/nsf

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Prepared default load options for the source file type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
