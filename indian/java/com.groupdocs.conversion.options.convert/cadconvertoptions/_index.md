---
title: "CadConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Cad प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Cad प्रकार में रूपांतरण के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [CadConvertOptions()](#CadConvertOptions--) | क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


रूपांतरण शुरू करने के लिए पृष्ठ संख्या प्राप्त करता है।


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


रूपांतरण शुरू करने के लिए पृष्ठ संख्या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


PageNumber से शुरू होने वाले रूपांतरण के लिए पृष्ठों की संख्या प्राप्त करता है।


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


PageNumber से शुरू होने वाले रूपांतरण के लिए पृष्ठों की संख्या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pagesCount | int |  |

