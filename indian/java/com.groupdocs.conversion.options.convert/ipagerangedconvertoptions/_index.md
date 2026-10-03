---
title: "IPageRangedConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "विशिष्ट पृष्ठों की सूची के रूपांतरण का समर्थन करने वाले रूपांतरण विकल्पों का प्रतिनिधित्व करता है"
type: docs
weight: 52
url: /hi/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

विशिष्ट पृष्ठों की सूची के रूपांतरण का समर्थन करने वाले रूपांतरण विकल्पों का प्रतिनिधित्व करता है

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPages()](#getPages--) | परिवर्तित करने के लिए पृष्ठ अनुक्रमणिकाओं की सूची प्राप्त करता है। |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | परिवर्तित करने के लिए पृष्ठ अनुक्रमणिकाओं की सूची सेट करता है। |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


कन्वर्ट किए जाने वाले पृष्ठ अनुक्रमणिकाओं की सूची प्राप्त करता है। विशिष्ट पृष्ठों को कन्वर्ट करने के लिए इसे निर्दिष्ट किया जाना चाहिए।


**Returns:**
java.util.List<java.lang.Integer> - परिवर्तित करने के लिए पृष्ठ अनुक्रमणिकाओं की सूची। विशिष्ट पृष्ठों को परिवर्तित करने के लिए इसे निर्दिष्ट किया जाना चाहिए।

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


कन्वर्ट किए जाने वाले पृष्ठ अनुक्रमणिकाओं की सूची सेट करता है। विशिष्ट पृष्ठों को कन्वर्ट करने के लिए इसे निर्दिष्ट किया जाना चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | परिवर्तित करने के लिए पृष्ठ अनुक्रमणिकाओं की सूची। विशिष्ट पृष्ठों को परिवर्तित करने के लिए इसे निर्दिष्ट किया जाना चाहिए। |
|

