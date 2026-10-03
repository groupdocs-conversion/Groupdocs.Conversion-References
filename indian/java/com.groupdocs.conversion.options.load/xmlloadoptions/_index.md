---
title: "XmlLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "XML दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 41
url: /hi/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

XML दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | नए उदाहरण को प्रारंभ करता है [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) क्लास। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | XSL-FO दस्तावेज़ स्ट्रीम को XSL का उपयोग करके XML-FO में परिवर्तित करने के लिए। |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL दस्तावेज़ स्ट्रीम को XSL का उपयोग करके XML-FO में परिवर्तित करने के लिए। |
|
|  | [getXsltFactory()](#getXsltFactory--) | XSL परिवर्तन करके XML को HTML में बदलने के लिए XSLT दस्तावेज़ स्ट्रीम प्राप्त करें। |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL परिवर्तन करके XML को HTML में बदलने के लिए XSLT दस्तावेज़ स्ट्रीम सेट करें। |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | Xml दस्तावेज़ को डेटा स्रोत के रूप में उपयोग करें |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | डेटा स्रोत के रूप में Xml दस्तावेज़ का उपयोग सेट करें |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


नए उदाहरण को प्रारंभ करता है [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) क्लास।


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


XSL-FO दस्तावेज़ स्ट्रीम को XSL का उपयोग करके XML-FO में परिवर्तित करने के लिए।


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


XSL दस्तावेज़ स्ट्रीम को XSL का उपयोग करके XML-FO में परिवर्तित करने के लिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


XSL परिवर्तन करके XML को HTML में बदलने के लिए XSLT दस्तावेज़ स्ट्रीम प्राप्त करें।


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


XSL परिवर्तन करके XML को HTML में बदलने के लिए XSLT दस्तावेज़ स्ट्रीम सेट करें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Xml दस्तावेज़ को डेटा स्रोत के रूप में उपयोग करें


**Returns:**
बूलियन - यदि उपयोग किया जाए तो true

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


डेटा स्रोत के रूप में Xml दस्तावेज़ का उपयोग सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | useAsDataSource | बूलियन | Xml दस्तावेज़ को डेटा स्रोत के रूप में उपयोग करें |
|

