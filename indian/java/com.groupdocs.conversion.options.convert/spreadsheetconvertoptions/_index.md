---
title: "SpreadsheetConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "स्प्रेडशीट फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 40
url: /hi/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

स्प्रेडशीट फ़ाइल प्रकार में रूपांतरण के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | नया उदाहरण प्रारंभ करता है [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) क्लास का। |
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
|  | [getSeparator()](#getSeparator--) | डिलिमिटेड फ़ॉर्मैट में परिवर्तित करने के समय उपयोग किए जाने वाले विभाजक को निर्दिष्ट करता है। |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


नया उदाहरण प्रारंभ करता है [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) क्लास का।


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


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। डिफ़ॉल्ट 100 है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


डिलिमिटेड फ़ॉर्मैट में परिवर्तित करने के समय उपयोग किए जाने वाले विभाजक को निर्दिष्ट करता है।


**Returns:**
चर
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विभाजक | चर |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


वांछित फ़ाइल प्रकार जिसमें इनपुट दस्तावेज़ को परिवर्तित किया जाना चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

