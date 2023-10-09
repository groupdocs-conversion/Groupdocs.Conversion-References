---
title: EmailFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Email file formats that are used by email applications to store their various data including email messages attachments folders address books etc.
type: docs
weight: 15
url: /java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Defines Email file formats that are used by email applications to store their various data including email messages, attachments, folders, address books etc. Includes the following file types: [Eml](../../com.groupdocs.conversion.filetypes/emailfiletype\#Eml), [Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype\#Emlx), [Msg](../../com.groupdocs.conversion.filetypes/emailfiletype\#Msg), [Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype\#Vcf). [Pst](../../com.groupdocs.conversion.filetypes/emailfiletype\#Pst). [Ost](../../com.groupdocs.conversion.filetypes/emailfiletype\#Ost). Learn more about Email formats [here][].


[here]: https://wiki.fileformat.com/email
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailFileType()](#EmailFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Msg](#Msg) | MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. |
| [Eml](#Eml) | EML file format represents email messages saved using Outlook and other relevant applications. |
| [Emlx](#Emlx) | The EMLX file format is implemented and developed by Apple. |
| [Vcf](#Vcf) | VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. |
| [Mbox](#Mbox) | MBox file format is a generic term that represents a container for collection of electronic mail messages. |
| [Pst](#Pst) | Files with .PST extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. |
| [Ost](#Ost) | OST or Offline Storage Files represent user's mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Serialization constructor

### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/msg

### Eml {#Eml}
```
public static final EmailFileType Eml
```


EML file format represents email messages saved using Outlook and other relevant applications. Almost all emailing clients support this file format for its compliance with RFC-822 Internet Message Format Standard. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/eml

### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


The EMLX file format is implemented and developed by Apple. The Apple Mail application uses the EMLX file format for exporting the emails. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/emlx

### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. The format is widely used for data interchange among popular information exchange applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/vcf

### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


MBox file format is a generic term that represents a container for collection of electronic mail messages. The messages are stored inside the container along with their attachments. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/email/mbox/

### Pst {#Pst}
```
public static final EmailFileType Pst
```


Files with .PST extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/pst

### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST or Offline Storage Files represent user's mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/ost

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Prepared default load options for the source file type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Prepared default convert options for the file type

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
