---
title: "ConversionNotSupportedException"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "GroupDocs अपवाद तब फेंका जाता है जब स्रोत फ़ाइल से लक्ष्य फ़ाइल प्रकार में रूपांतरण समर्थित नहीं होता।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

GroupDocs अपवाद तब फेंका जाता है जब स्रोत फ़ाइल से लक्ष्य फ़ाइल प्रकार में रूपांतरण समर्थित नहीं होता।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | डिफ़ॉल्ट कंस्ट्रक्टर |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | एक स्रोत FileType और एक लक्ष्य Filetype के साथ अपवाद का उदाहरण बनाता है |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | संदेश के साथ एक अपवाद इंस्टेंस बनाता है |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


डिफ़ॉल्ट कंस्ट्रक्टर


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


एक स्रोत FileType और एक लक्ष्य Filetype के साथ अपवाद का उदाहरण बनाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | स्रोत फ़ाइल प्रकार |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | लक्ष्य फ़ाइल प्रकार |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


संदेश के साथ एक अपवाद इंस्टेंस बनाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | संदेश |
|

