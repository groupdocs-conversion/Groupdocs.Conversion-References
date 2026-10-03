---
title: "TxtLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "टेक्स्ट दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 34
url: /hi/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

टेक्स्ट दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) वर्ग का नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | सादा पाठ दस्तावेज़ को परिवर्तित करते समय क्रमांकित सूची आइटम कैसे पहचाने जाएँ, इसे निर्दिष्ट करने की अनुमति देता है। |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | सादा पाठ दस्तावेज़ को परिवर्तित करते समय क्रमांकित सूची आइटम कैसे पहचाने जाएँ, इसे निर्दिष्ट करने की अनुमति देता है। |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | ट्रेलिंग स्पेस हैंडलिंग का पसंदीदा विकल्प प्राप्त करता है या सेट करता है। |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | ट्रेलिंग स्पेस हैंडलिंग का पसंदीदा विकल्प प्राप्त करता है या सेट करता है। |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | लीडिंग स्पेस हैंडलिंग का पसंदीदा विकल्प प्राप्त करता है या सेट करता है। |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | लीडिंग स्पेस हैंडलिंग का पसंदीदा विकल्प प्राप्त करता है या सेट करता है। |
|
|  | [getEncoding()](#getEncoding--) | Txt दस्तावेज़ लोड करने पर उपयोग किए जाने वाले एन्कोडिंग को प्राप्त करता है या सेट करता है। |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Txt दस्तावेज़ लोड करने पर उपयोग किए जाने वाले एन्कोडिंग को प्राप्त करता है या सेट करता है। |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


[TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) वर्ग का नया उदाहरण प्रारंभ करता है।


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


सादा पाठ दस्तावेज़ को परिवर्तित करते समय क्रमांकित सूची आइटम कैसे पहचाने जाएँ, इसे निर्दिष्ट करने की अनुमति देता है।
डिफ़ॉल्ट मान true है।

<br />

*** ** * ** ***

यदि यह विकल्प false पर सेट किया जाता है, तो सूची पहचान एल्गोरिदम सूची पैराग्राफ का पता लगाता है, जब सूची संख्याएँ ... के साथ समाप्त होती हैं।
या तो बिंदु, दायाँ कोष्ठक या बुलेट प्रतीक (जैसे "\u2022", "*", "-" या "o").

यदि यह विकल्प true पर सेट किया जाता है, तो व्हाइटस्पेस भी सूची संख्या विभाजकों के रूप में उपयोग किए जाते हैं:
अरबी शैली की क्रमांकन (1., 1.1.2.) के लिए सूची पहचान एल्गोरिदम व्हाइटस्पेस और बिंदु (".") दोनों प्रतीकों का उपयोग करता है।

<br />



**Returns:**
बूलियन
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


सादा पाठ दस्तावेज़ को परिवर्तित करते समय क्रमांकित सूची आइटम कैसे पहचाने जाएँ, इसे निर्दिष्ट करने की अनुमति देता है।
डिफ़ॉल्ट मान true है।

<br />

*** ** * ** ***

यदि यह विकल्प false पर सेट किया जाता है, तो सूची पहचान एल्गोरिदम सूची पैराग्राफ का पता लगाता है, जब सूची संख्याएँ ... के साथ समाप्त होती हैं।
या तो बिंदु, दायाँ कोष्ठक या बुलेट प्रतीक (जैसे "\u2022", "*", "-" या "o").

यदि यह विकल्प true पर सेट किया जाता है, तो व्हाइटस्पेस भी सूची संख्या विभाजकों के रूप में उपयोग किए जाते हैं:
अरबी शैली की क्रमांकन (1., 1.1.2.) के लिए सूची पहचान एल्गोरिदम व्हाइटस्पेस और बिंदु (".") दोनों प्रतीकों का उपयोग करता है।

<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


ट्रेलिंग स्पेस हैंडलिंग का पसंदीदा विकल्प प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान है [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


ट्रेलिंग स्पेस हैंडलिंग का पसंदीदा विकल्प प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान है [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


लीडिंग स्पेस हैंडलिंग का पसंदीदा विकल्प प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान है [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


लीडिंग स्पेस हैंडलिंग का पसंदीदा विकल्प प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान है [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Txt दस्तावेज़ लोड करते समय उपयोग की जाने वाली एन्कोडिंग प्राप्त करता है या सेट करता है। यह null हो सकता है। डिफ़ॉल्ट null है।


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Txt दस्तावेज़ लोड करते समय उपयोग की जाने वाली एन्कोडिंग प्राप्त करता है या सेट करता है। यह null हो सकता है। डिफ़ॉल्ट null है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset |  |

