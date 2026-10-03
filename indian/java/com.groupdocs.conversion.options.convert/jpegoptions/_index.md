---
title: "JpegOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Jpeg फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 20
url: /hi/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Jpeg फ़ाइल प्रकार में रूपांतरण के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | नया उदाहरण प्रारंभ करता है [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) क्लास का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getQuality()](#getQuality--) | वांछित छवि गुणवत्ता। |
|
|  | [setQuality(int value)](#setQuality-int-) | वांछित छवि गुणवत्ता। |
|
|  | [getColorMode()](#getColorMode--) | Jpg रंग मोड। |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Jpg रंग मोड। |
|
|  | [getCompression()](#getCompression--) | Jpg संपीड़न विधि। |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Jpg संपीड़न विधि। |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


नया उदाहरण प्रारंभ करता है [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) क्लास का।


### getQuality() {#getQuality--}
```
public final int getQuality()
```


वांछित छवि गुणवत्ता। मान 0 और 100 के बीच होना चाहिए। डिफ़ॉल्ट मान 100 है।


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


वांछित छवि गुणवत्ता। मान 0 और 100 के बीच होना चाहिए। डिफ़ॉल्ट मान 100 है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Jpg रंग मोड।


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Jpg रंग मोड।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Jpg संपीड़न विधि।


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Jpg संपीड़न विधि।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

