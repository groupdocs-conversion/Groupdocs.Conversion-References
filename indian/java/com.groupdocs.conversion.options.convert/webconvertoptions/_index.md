---
title: "WebConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Web फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 46
url: /hi/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Web फ़ाइल प्रकार में रूपांतरण के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | मुख्य HTML के भीतर फ़ॉन्ट संसाधनों को एम्बेड करना चाहिए या नहीं, यह निर्दिष्ट करता है। |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | मुख्य HTML के भीतर फ़ॉन्ट संसाधनों को एम्बेड करना चाहिए या नहीं, यह निर्दिष्ट करता है। |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
बूलियन
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| usePdf | बूलियन |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
बूलियन
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fixedLayout | बूलियन |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
बूलियन
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fixedLayoutShowBorders | बूलियन |  |

### getZoom() {#getZoom--}
```
public int getZoom()
```




**Returns:**
int
### setZoom(int zoom) {#setZoom-int-}
```
public void setZoom(int zoom)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


निर्दिष्ट करता है कि मुख्य HTML के भीतर फ़ॉन्ट संसाधनों को एम्बेड किया जाए या नहीं। डिफ़ॉल्ट रूप में false है। नोट: यदि FixedLayout को true पर सेट किया जाता है, तो फ़ॉन्ट संसाधन हमेशा एम्बेड किए जाएंगे।


**Returns:**
बूलियन
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


निर्दिष्ट करता है कि मुख्य HTML के भीतर फ़ॉन्ट संसाधनों को एम्बेड किया जाए या नहीं। डिफ़ॉल्ट रूप में false है। नोट: यदि FixedLayout को true पर सेट किया जाता है, तो फ़ॉन्ट संसाधन हमेशा एम्बेड किए जाएंगे।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| embedFontResources | बूलियन |  |

