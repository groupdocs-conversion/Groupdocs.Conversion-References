---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载 CSV 文档的选项。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

加载 CSV 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | 初始化 [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Csv 文件的分隔符。 |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Csv 文件的分隔符。 |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True 表示文件包含多种编码。 |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True 表示文件包含多种编码。 |
|
|  | [hasFormula()](#hasFormula--) | 指示当文本以 "=" 开头时是否为公式。 |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | 指示当文本以 "=" 开头时是否为公式。 |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | 指示文件中的字符串是否转换为数值。 |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | 指示文件中的字符串是否转换为数值。 |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | 指示文件中的字符串是否转换为日期。 |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | 指示文件中的字符串是否转换为日期。 |
|
|  | [getEncoding()](#getEncoding--) | 编码。 |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 编码。 |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


初始化 [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) 类的新实例。


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Csv 文件的分隔符。


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Csv 文件的分隔符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True 表示文件包含多种编码。


**Returns:**
布尔
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True 表示文件包含多种编码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


指示当文本以 "=" 开头时是否为公式。


**Returns:**
布尔
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


指示当文本以 "=" 开头时是否为公式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


指示文件中的字符串是否转换为数值。默认是 True。


**Returns:**
布尔
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


指示文件中的字符串是否转换为数值。默认是 True。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


指示文件中的字符串是否转换为日期。默认是 True。


**Returns:**
布尔
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


指示文件中的字符串是否转换为日期。默认是 True。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


编码。默认是 Encoding.Default。


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


编码。默认是 Encoding.Default。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.Text.Encoding |  |

