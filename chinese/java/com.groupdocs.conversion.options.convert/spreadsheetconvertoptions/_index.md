---
title: "SpreadsheetConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "用于转换为 Spreadsheet 文件类型的选项。"
type: docs
weight: 40
url: /zh/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

用于转换为 Spreadsheet 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | 初始化 [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 如果您想使用密码保护转换后的文档，请设置此属性。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 如果您想使用密码保护转换后的文档，请设置此属性。 |
|
|  | [getZoom()](#getZoom--) | 指定缩放比例（百分比）。 |
|
|  | [setZoom(int value)](#setZoom-int-) | 指定缩放比例（百分比）。 |
|
|  | [getSeparator()](#getSeparator--) | 指定在转换为分隔格式时使用的分隔符 |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


初始化 [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) 类的新实例。


### getPassword() {#getPassword--}
```
public final String getPassword()
```


如果您想使用密码保护转换后的文档，请设置此属性。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


如果您想使用密码保护转换后的文档，请设置此属性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


指定缩放比例（百分比）。默认值为 100。


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


指定缩放比例（百分比）。默认值为 100。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


指定在转换为分隔格式时使用的分隔符


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 分隔符 | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


所需的文件类型，输入文档应转换为该类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

