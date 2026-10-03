---
title: "PresentationConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "प्रेजेंटेशन फ़ाइल प्रकार में रूपांतरण के विकल्पों का वर्णन करता है।"
type: docs
weight: 33
url: /hi/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

प्रेजेंटेशन फ़ाइल प्रकार में रूपांतरण के विकल्पों का वर्णन करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | नया उदाहरण प्रारंभ करता है [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) क्लास का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPassword()](#getPassword--) | यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस प्रॉपर्टी को सेट करें। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस प्रॉपर्टी को सेट करें। |
|
|  | [getZoom()](#getZoom--) | ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। |
|
|  | [setZoom(int value)](#setZoom-int-) | ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। |
|
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


नया उदाहरण प्रारंभ करता है [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) क्लास का।


### getPassword() {#getPassword--}
```
public final String getPassword()
```


यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस प्रॉपर्टी को सेट करें।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस प्रॉपर्टी को सेट करें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। डिफ़ॉल्ट 100 है।
डिफ़ॉल्ट ज़ूम Microsoft Powerpoint 2010 तक समर्थित है। Microsoft Powerpoint 2013 से शुरू होकर डिफ़ॉल्ट ज़ूम अब दस्तावेज़ पर सेट नहीं किया जाता, बल्कि यह खुली हुई अंतिम दस्तावेज़ के ज़ूम फैक्टर को उपयोग करता दिखता है।


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। डिफ़ॉल्ट 100 है।
डिफ़ॉल्ट ज़ूम Microsoft Powerpoint 2010 तक समर्थित है। Microsoft Powerpoint 2013 से शुरू होकर डिफ़ॉल्ट ज़ूम अब दस्तावेज़ पर सेट नहीं किया जाता, बल्कि यह खुली हुई अंतिम दस्तावेज़ के ज़ूम फैक्टर को उपयोग करता दिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

