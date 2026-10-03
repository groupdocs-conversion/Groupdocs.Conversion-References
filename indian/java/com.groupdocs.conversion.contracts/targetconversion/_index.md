---
title: "TargetConversion"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "संभव लक्ष्य रूपांतरण और यह प्राथमिक है या द्वितीयक है, यह फ़्लैग दर्शाता है"
type: docs
weight: 14
url: /hi/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

संभव लक्ष्य रूपांतरण और यह प्राथमिक है या द्वितीयक है, यह फ़्लैग दर्शाता है

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | लक्ष्य दस्तावेज़ प्रारूप |
|
|  | [isPrimary()](#isPrimary--) | क्या रूपांतरण प्राथमिक है |
|
|  | [getConvertOptions()](#getConvertOptions--) | पूर्वनिर्धारित रूपांतरण विकल्प जो वर्तमान प्रकार में रूपांतरित करने के लिए उपयोग किए जा सकते हैं |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


लक्ष्य दस्तावेज़ प्रारूप


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


क्या रूपांतरण प्राथमिक है


**Returns:**
बूलियन - यदि प्राथमिक हो तो `true`

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


पूर्वनिर्धारित रूपांतरण विकल्प जो वर्तमान प्रकार में रूपांतरित करने के लिए उपयोग किए जा सकते हैं


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

