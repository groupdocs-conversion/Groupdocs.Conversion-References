---
title: "CsvLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Csv दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Csv दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | नया उदाहरण इनिशियलाइज़ करता है [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) क्लास का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Csv फ़ाइल का डिलिमिटर। |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Csv फ़ाइल का डिलिमिटर। |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True का अर्थ है फ़ाइल में कई एन्कोडिंग्स हैं। |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True का अर्थ है फ़ाइल में कई एन्कोडिंग्स हैं। |
|
|  | [hasFormula()](#hasFormula--) | इंगित करता है कि यदि टेक्स्ट "=" से शुरू होता है तो वह फ़ॉर्मूला है या नहीं। |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | इंगित करता है कि यदि टेक्स्ट "=" से शुरू होता है तो वह फ़ॉर्मूला है या नहीं। |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | इंगित करता है कि फ़ाइल में स्ट्रिंग को संख्यात्मक में परिवर्तित किया गया है या नहीं। |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | इंगित करता है कि फ़ाइल में स्ट्रिंग को संख्यात्मक में परिवर्तित किया गया है या नहीं। |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | इंगित करता है कि फ़ाइल में स्ट्रिंग को तिथि में परिवर्तित किया गया है या नहीं। |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | इंगित करता है कि फ़ाइल में स्ट्रिंग को तिथि में परिवर्तित किया गया है या नहीं। |
|
|  | [getEncoding()](#getEncoding--) | एन्कोडिंग। |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | एन्कोडिंग। |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


नया उदाहरण इनिशियलाइज़ करता है [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) क्लास का।


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Csv फ़ाइल का डिलिमिटर।


**Returns:**
चर
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Csv फ़ाइल का डिलिमिटर।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | चर |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True का अर्थ है फ़ाइल में कई एन्कोडिंग्स हैं।


**Returns:**
बूलियन
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True का अर्थ है फ़ाइल में कई एन्कोडिंग्स हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


इंगित करता है कि यदि टेक्स्ट "=" से शुरू होता है तो वह फ़ॉर्मूला है या नहीं।


**Returns:**
बूलियन
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


इंगित करता है कि यदि टेक्स्ट "=" से शुरू होता है तो वह फ़ॉर्मूला है या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


यह दर्शाता है कि फ़ाइल में स्ट्रिंग को संख्यात्मक में परिवर्तित किया गया है या नहीं। डिफ़ॉल्ट True है।


**Returns:**
बूलियन
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


यह दर्शाता है कि फ़ाइल में स्ट्रिंग को संख्यात्मक में परिवर्तित किया गया है या नहीं। डिफ़ॉल्ट True है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


यह दर्शाता है कि फ़ाइल में स्ट्रिंग को तिथि में परिवर्तित किया गया है या नहीं। डिफ़ॉल्ट True है।


**Returns:**
बूलियन
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


यह दर्शाता है कि फ़ाइल में स्ट्रिंग को तिथि में परिवर्तित किया गया है या नहीं। डिफ़ॉल्ट True है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


एन्कोडिंग। डिफ़ॉल्ट Encoding.Default है।


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


एन्कोडिंग। डिफ़ॉल्ट Encoding.Default है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.ms.System.Text.Encoding |  |

