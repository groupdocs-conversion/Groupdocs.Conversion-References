---
title: "ConverterSettings"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है [Converter](../../com.groupdocs.conversion/converter)।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getCache()](#getCache--) | परिवर्तन परिणामों को संग्रहीत करने के लिए उपयोग किया गया कैश कार्यान्वयन। |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | परिवर्तन परिणामों को संग्रहीत करने के लिए उपयोग किया गया कैश कार्यान्वयन। |
|
|  | [getLogger()](#getLogger--) | परिवर्तन प्रक्रिया को लॉग करने के लिए उपयोग किया गया लॉगर कार्यान्वयन। |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | परिवर्तन प्रक्रिया को लॉग करने के लिए उपयोग किया गया लॉगर कार्यान्वयन। |
|
|  | [getListener()](#getListener--) | परिवर्तन स्थिति और प्रगति की निगरानी के लिए उपयोग किए जाने वाले कनवर्टर लिस्नर कार्यान्वयन को प्राप्त करता है |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | परिवर्तन स्थिति और प्रगति की निगरानी के लिए उपयोग किए जाने वाले कनवर्टर लिस्नर कार्यान्वयन को सेट करता है |
|
|  | [getFontDirectories()](#getFontDirectories--) | कस्टम फ़ॉन्ट निर्देशिकाओं के पथ |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | कस्टम फ़ॉन्ट निर्देशिकाओं के पथ |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | परिवर्तन के लिए उपयोग किया गया अस्थायी फ़ोल्डर |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | परिवर्तन के लिए उपयोग किया गया अस्थायी फ़ोल्डर सेट करता है |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


परिवर्तन परिणामों को संग्रहीत करने के लिए उपयोग किया गया कैश कार्यान्वयन।


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


परिवर्तन परिणामों को संग्रहीत करने के लिए उपयोग किया गया कैश कार्यान्वयन।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


परिवर्तन प्रक्रिया को लॉग करने के लिए उपयोग किया गया लॉगर कार्यान्वयन।


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


परिवर्तन प्रक्रिया को लॉग करने के लिए उपयोग किया गया लॉगर कार्यान्वयन।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


परिवर्तन स्थिति और प्रगति की निगरानी के लिए उपयोग किए जाने वाले कनवर्टर लिस्नर कार्यान्वयन को प्राप्त करता है


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


परिवर्तन स्थिति और प्रगति की निगरानी के लिए उपयोग किए जाने वाले कनवर्टर लिस्नर कार्यान्वयन को सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | कनवर्टर लिस्नर |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


कस्टम फ़ॉन्ट निर्देशिकाओं के पथ


**Returns:**
java.util.List<java.lang.String>
### getFontDirectoriesInternal() {#getFontDirectoriesInternal--}
```
public List<String> getFontDirectoriesInternal()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


कस्टम फ़ॉन्ट निर्देशिकाओं के पथ


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<java.lang.String> |  |

### listConverterSettings() {#listConverterSettings--}
```
public List<String> listConverterSettings()
```




**Returns:**
java.util.List<java.lang.String>
### getTempFolder() {#getTempFolder--}
```
public String getTempFolder()
```


परिवर्तन के लिए उपयोग किया गया अस्थायी फ़ोल्डर


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


परिवर्तन के लिए उपयोग किया गया अस्थायी फ़ोल्डर सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

