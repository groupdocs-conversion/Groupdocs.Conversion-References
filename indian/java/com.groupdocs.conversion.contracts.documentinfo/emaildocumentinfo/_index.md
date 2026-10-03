---
title: "EmailDocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "ईमेल दस्तावेज़ मेटाडेटा शामिल है"
type: docs
weight: 17
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

ईमेल दस्तावेज़ मेटाडेटा शामिल है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isSigned()](#isSigned--) | साइन किया गया प्राप्त करता है |
|
|  | [isEncrypted()](#isEncrypted--) | प्राप्त करता है एन्क्रिप्टेड है |
|
|  | [isHtml()](#isHtml--) | HTML प्राप्त करता है |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | संलग्नकों की गिनती प्राप्त करता है |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | संलग्नकों के नाम प्राप्त करता है |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मेल | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| आकार | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


साइन किया गया प्राप्त करता है


**Returns:**
बूलियन - यदि साइन किया गया हो तो सत्य

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


प्राप्त करता है एन्क्रिप्टेड है


**Returns:**
बूलियन - यदि एन्क्रिप्टेड हो तो सत्य

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


HTML प्राप्त करता है


**Returns:**
बूलियन - यदि HTML हो तो सत्य

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


संलग्नकों की गिनती प्राप्त करता है


**Returns:**
इंट - संलग्नकों की गिनती

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


संलग्नकों के नाम प्राप्त करता है


**Returns:**
java.util.List<java.lang.String> - संलग्नकों के नाम

