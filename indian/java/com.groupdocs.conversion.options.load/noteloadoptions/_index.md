---
title: "NoteLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "वन दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 24
url: /hi/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

वन दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) वर्ग का नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Note दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Note दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Note दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट को प्रतिस्थापित करें। |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Note दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट को प्रतिस्थापित करें। |
|
|  | [getPassword()](#getPassword--) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


[NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) वर्ग का नया उदाहरण प्रारंभ करता है।


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Note दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि फ़ॉन्ट अनुपलब्ध है तो निम्न फ़ॉन्ट उपयोग किया जाएगा।


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Note दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि फ़ॉन्ट अनुपलब्ध है तो निम्न फ़ॉन्ट उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Note दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट को प्रतिस्थापित करें।


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Note दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट को प्रतिस्थापित करें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

