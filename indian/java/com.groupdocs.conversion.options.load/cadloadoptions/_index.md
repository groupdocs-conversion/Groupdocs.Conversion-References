---
title: "CadLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "CAD दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

CAD दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [CadLoadOptions()](#CadLoadOptions--) | नए उदाहरण को प्रारंभ करता है [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) क्लास। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getLayoutNames()](#getLayoutNames--) | कौन से CAD लेआउट को परिवर्तित किया जाना है, यह निर्दिष्ट करता है |
|
|  | [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | कौन से CAD लेआउट को परिवर्तित किया जाना है, यह निर्दिष्ट करता है |
|
|  | [getDrawType()](#getDrawType--) | ड्राइंग का प्रकार प्राप्त करता है। |
|
|  | [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | ड्राइंग का प्रकार सेट करता है। |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | पृष्ठभूमि रंग प्राप्त करता है। |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | पृष्ठभूमि रंग सेट करता है। |
|
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
|  | [getCtbSources()](#getCtbSources--) | CTB स्रोत प्राप्त करता है। |
|
|  | [setCtbSources(Map<String,InputStream> ctbSources)](#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--) | CTB स्रोत सेट करता है। |
|
|  | [getDrawColor()](#getDrawColor--) | अग्रभूमि रंग प्राप्त करता है। |
|
|  | [setDrawColor(System.Drawing.Color drawColor)](#setDrawColor-com.aspose.ms.System.Drawing.Color-) | अग्रभूमि रंग सेट करता है। |
|
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


नए उदाहरण को प्रारंभ करता है [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) क्लास।


### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


कौन से CAD लेआउट को परिवर्तित किया जाना है, यह निर्दिष्ट करता है


**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


कौन से CAD लेआउट को परिवर्तित किया जाना है, यह निर्दिष्ट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


ड्राइंग का प्रकार प्राप्त करता है।


**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


ड्राइंग का प्रकार सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


पृष्ठभूमि रंग प्राप्त करता है।


**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


पृष्ठभूमि रंग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

### getCtbSources() {#getCtbSources--}
```
public Map<String,InputStream> getCtbSources()
```


CTB स्रोत प्राप्त करता है।


**Returns:**
java.util.Map<java.lang.String,java.io.InputStream>
### setCtbSources(Map<String,InputStream> ctbSources) {#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--}
```
public void setCtbSources(Map<String,InputStream> ctbSources)
```


CTB स्रोत सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ctbSources | java.util.Map<java.lang.String,java.io.InputStream> |  |

### getDrawColor() {#getDrawColor--}
```
public System.Drawing.Color getDrawColor()
```


अग्रभूमि रंग प्राप्त करता है।


**Returns:**
com.aspose.ms.System.Drawing.Color
### setDrawColor(System.Drawing.Color drawColor) {#setDrawColor-com.aspose.ms.System.Drawing.Color-}
```
public void setDrawColor(System.Drawing.Color drawColor)
```


अग्रभूमि रंग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| drawColor | com.aspose.ms.System.Drawing.Color |  |

