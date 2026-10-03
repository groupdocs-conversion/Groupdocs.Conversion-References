---
title: "DiagramLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "डायग्राम दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

डायग्राम दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DiagramLoadOptions()](#DiagramLoadOptions--) | नए उदाहरण को प्रारंभ करता है [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) क्लास। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | डायग्राम दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | डायग्राम दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


नए उदाहरण को प्रारंभ करता है [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) क्लास।


### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


डायग्राम दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


डायग्राम दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

