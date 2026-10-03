---
title: "WordProcessingBookmarksOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "WordProcessing में बुकमार्क संभालने के विकल्प"
type: docs
weight: 39
url: /hi/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

WordProcessing में बुकमार्क संभालने के विकल्प

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | दस्तावेज़ रूपरेखा में वह डिफ़ॉल्ट स्तर निर्दिष्ट करता है जिस पर Word बुकमार्क प्रदर्शित किए जाएंगे। |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | दस्तावेज़ रूपरेखा में वह डिफ़ॉल्ट स्तर निर्दिष्ट करता है जिस पर Word बुकमार्क प्रदर्शित किए जाएंगे। |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | दस्तावेज़ रूपरेखा में शामिल करने के लिए शीर्षकों (हेडिंग शैलियों के साथ स्वरूपित पैराग्राफ) के स्तरों की संख्या निर्दिष्ट करता है। |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | दस्तावेज़ रूपरेखा में शामिल करने के लिए शीर्षकों (हेडिंग शैलियों के साथ स्वरूपित पैराग्राफ) के स्तरों की संख्या निर्दिष्ट करता है। |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | फ़ाइल को देखा जाने पर दस्तावेज़ रूपरेखा में विस्तारित दिखाने के लिए स्तरों की संख्या निर्दिष्ट करता है। |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | फ़ाइल को देखा जाने पर दस्तावेज़ रूपरेखा में विस्तारित दिखाने के लिए स्तरों की संख्या निर्दिष्ट करता है। |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


दस्तावेज़ रूपरेखा में वह डिफ़ॉल्ट स्तर निर्दिष्ट करता है जिस पर Word बुकमार्क दिखाए जाएंगे। डिफ़ॉल्ट 0 है। वैध सीमा 0 से 9 है।


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


दस्तावेज़ रूपरेखा में वह डिफ़ॉल्ट स्तर निर्दिष्ट करता है जिस पर Word बुकमार्क दिखाए जाएंगे। डिफ़ॉल्ट 0 है। वैध सीमा 0 से 9 है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


दस्तावेज़ रूपरेखा में शामिल करने के लिए शीर्षकों (हेडिंग शैलियों के साथ स्वरूपित पैराग्राफ) के स्तरों की संख्या निर्दिष्ट करता है। डिफ़ॉल्ट 0 है। वैध सीमा 0 से 9 है।


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


दस्तावेज़ रूपरेखा में शामिल करने के लिए शीर्षकों (हेडिंग शैलियों के साथ स्वरूपित पैराग्राफ) के स्तरों की संख्या निर्दिष्ट करता है। डिफ़ॉल्ट 0 है। वैध सीमा 0 से 9 है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


फ़ाइल को देखा जाने पर दस्तावेज़ रूपरेखा में विस्तारित दिखाने के लिए स्तरों की संख्या निर्दिष्ट करता है। डिफ़ॉल्ट 0 है। वैध सीमा 0 से 9 है। ध्यान दें कि यह विकल्प XPS में सहेजते समय काम नहीं करेगा।


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


फ़ाइल को देखा जाने पर दस्तावेज़ रूपरेखा में विस्तारित दिखाने के लिए स्तरों की संख्या निर्दिष्ट करता है। डिफ़ॉल्ट 0 है। वैध सीमा 0 से 9 है। ध्यान दें कि यह विकल्प XPS में सहेजते समय काम नहीं करेगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

