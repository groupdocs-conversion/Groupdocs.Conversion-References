---
title: "IPagedConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "स्टार्ट पेज और पेज काउंट निर्दिष्ट करके पेज सीमा लागू करने की अनुमति देने वाले रूपांतरण विकल्पों का प्रतिनिधित्व करता है"
type: docs
weight: 55
url: /hi/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

स्टार्ट पेज और पेज काउंट निर्दिष्ट करके पेज सीमा लागू करने की अनुमति देने वाले रूपांतरण विकल्पों का प्रतिनिधित्व करता है

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | रूपांतरण शुरू करने के लिए पृष्ठ संख्या प्राप्त करता है। |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | रूपांतरण शुरू करने के लिए पृष्ठ संख्या सेट करता है। |
|
|  | [getPagesCount()](#getPagesCount--) | PageNumber से शुरू होने वाले रूपांतरण के लिए पृष्ठों की संख्या प्राप्त करता है। |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | PageNumber से शुरू होने वाले रूपांतरण के लिए पृष्ठों की संख्या सेट करता है। |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


रूपांतरण शुरू करने के लिए पृष्ठ संख्या प्राप्त करता है।


**Returns:**
java.lang.Integer - वह पृष्ठ संख्या जिससे परिवर्तन शुरू किया जाना है।

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


रूपांतरण शुरू करने के लिए पृष्ठ संख्या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | pageNumber | int | परिवर्तन शुरू करने के लिए पृष्ठ संख्या। |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


PageNumber से शुरू होने वाले रूपांतरण के लिए पृष्ठों की संख्या प्राप्त करता है।


**Returns:**
java.lang.Integer - PageNumber से शुरू होकर परिवर्तित करने वाले पृष्ठों की संख्या।

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


PageNumber से शुरू होने वाले रूपांतरण के लिए पृष्ठों की संख्या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | pagesCount | int | PageNumber से शुरू होकर परिवर्तित करने वाले पृष्ठों की संख्या। |
|

