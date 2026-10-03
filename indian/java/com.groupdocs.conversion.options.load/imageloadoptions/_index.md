---
title: "ImageLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "इमेज दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 21
url: /hi/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

इमेज दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | नया उदाहरण प्रारंभ करता है [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) क्लास। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Psd, Emf, Wmf दस्तावेज़ प्रकारों के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Psd, Emf, Wmf दस्तावेज़ प्रकारों के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | इमेज OCR कनेक्टर सेट करें |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | दस्तावेज़ लोड करने से पहले फ़ॉन्ट फ़ोल्डर रीसेट करें |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


नया उदाहरण प्रारंभ करता है [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) क्लास।


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Psd, Emf, Wmf दस्तावेज़ प्रकारों के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Psd, Emf, Wmf दस्तावेज़ प्रकारों के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### isRecognitionEnabled() {#isRecognitionEnabled--}
```
public boolean isRecognitionEnabled()
```




**Returns:**
बूलियन
### getOcrConnector() {#getOcrConnector--}
```
public IOcrConnector getOcrConnector()
```




**Returns:**
[IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector)
### setOcrConnector(IOcrConnector ocrConnector) {#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-}
```
public void setOcrConnector(IOcrConnector ocrConnector)
```


इमेज OCR कनेक्टर सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | OCR कनेक्टर इंस्टेंस |
|

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


दस्तावेज़ लोड करने से पहले फ़ॉन्ट फ़ोल्डर रीसेट करें


**Returns:**
बूलियन
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resetFontFolders | बूलियन |  |

