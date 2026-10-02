---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载 Txt 文档的选项。"
type: docs
weight: 34
url: /zh/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

加载 Txt 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | 初始化 [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | 允许指定在转换纯文本文档时如何识别编号列表项。 |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | 允许指定在转换纯文本文档时如何识别编号列表项。 |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | 获取或设置尾随空格处理的首选选项。 |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | 获取或设置尾随空格处理的首选选项。 |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | 获取或设置前导空格处理的首选选项。 |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | 获取或设置前导空格处理的首选选项。 |
|
|  | [getEncoding()](#getEncoding--) | 获取或设置加载 Txt 文档时使用的编码。 |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 获取或设置加载 Txt 文档时使用的编码。 |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


初始化 [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) 类的新实例。


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


输入文档文件类型


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


允许指定在转换纯文本文档时如何识别编号列表项。
默认值为 true。

<br />

*** ** * ** ***

如果此选项设置为 false，列表识别算法将在列表编号以以下字符结束时检测列表段落，
点号、右括号或项目符号（例如 "\u2022", "*", "-" 或 "o"）。

如果此选项设置为 true，空白字符也将用作列表编号分隔符：
阿拉伯式编号（1., 1.1.2.）的列表识别算法同时使用空白字符和点号（"."）符号。

<br />



**Returns:**
布尔
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


允许指定在转换纯文本文档时如何识别编号列表项。
默认值为 true。

<br />

*** ** * ** ***

如果此选项设置为 false，列表识别算法将在列表编号以以下字符结束时检测列表段落，
点号、右括号或项目符号（例如 "\u2022", "*", "-" 或 "o"）。

如果此选项设置为 true，空白字符也将用作列表编号分隔符：
阿拉伯式编号（1., 1.1.2.）的列表识别算法同时使用空白字符和点号（"."）符号。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


获取或设置尾随空格处理的首选选项。
默认值是 [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim)。


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


获取或设置尾随空格处理的首选选项。
默认值是 [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


获取或设置前导空格处理的首选选项。
默认值是 [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent)。


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


获取或设置前导空格处理的首选选项。
默认值是 [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


获取或设置加载 Txt 文档时使用的编码。可以为 null。默认值为 null。


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


获取或设置加载 Txt 文档时使用的编码。可以为 null。默认值为 null。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset |  |

