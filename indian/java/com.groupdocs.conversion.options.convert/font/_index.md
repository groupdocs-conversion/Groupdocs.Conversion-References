---
title: "फ़ॉन्ट"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "फ़ॉन्ट सेटिंग्स"
type: docs
weight: 16
url: /hi/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

फ़ॉन्ट सेटिंग्स

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | नया फ़ॉन्ट उदाहरण बनाता है |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | फ़ॉन्ट परिवार का नाम प्राप्त करता है |
|
|  | [getSize()](#getSize--) | फ़ॉन्ट आकार प्राप्त करता है |
|
|  | [isBold()](#isBold--) | फ़ॉन्ट बोल्ड फ़्लैग |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | फ़ॉन्ट बोल्ड फ़्लैग सेट करता है |
|
|  | [isItalic()](#isItalic--) | फ़ॉन्ट इटैलिक फ़्लैग |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | फ़ॉन्ट इटैलिक फ़्लैग सेट करता है |
|
|  | [isUnderline()](#isUnderline--) | फ़ॉन्ट अंडरलाइन प्राप्त करता है |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | फ़ॉन्ट अंडरलाइन सेट करता है |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


नया फ़ॉन्ट उदाहरण बनाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | फ़ॉन्ट नाम |
|
|  | आकार | float | फ़ॉन्ट आकार |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


फ़ॉन्ट परिवार का नाम प्राप्त करता है


**Returns:**
java.lang.String - फ़ॉन्ट फ़ैमिली नाम

### getSize() {#getSize--}
```
public float getSize()
```


फ़ॉन्ट आकार प्राप्त करता है


**Returns:**
float - फ़ॉन्ट आकार

### isBold() {#isBold--}
```
public boolean isBold()
```


फ़ॉन्ट बोल्ड फ़्लैग


**Returns:**
boolean - यदि बोल्ड हो तो true

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


फ़ॉन्ट बोल्ड फ़्लैग सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | बोल्ड | बूलियन | यदि बोल्ड हो तो true |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


फ़ॉन्ट इटैलिक फ़्लैग


**Returns:**
boolean - यदि इटैलिक हो तो true

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


फ़ॉन्ट इटैलिक फ़्लैग सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | इटैलिक | बूलियन | यदि इटैलिक हो तो true |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


फ़ॉन्ट अंडरलाइन प्राप्त करता है


**Returns:**
boolean - यदि फ़ॉन्ट अंडरलाइन है तो true

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


फ़ॉन्ट अंडरलाइन सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | अंडरलाइन | बूलियन | फ़ॉन्ट अंडरलाइन फ़्लैग |
|

### getDefault() {#getDefault--}
```
public static Font getDefault()
```




**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
### clone(float newSize) {#clone-float-}
```
public Font clone(float newSize)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
