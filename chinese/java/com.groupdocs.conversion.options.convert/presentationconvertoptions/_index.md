---
title: "PresentationConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "描述转换为 Presentation 文件类型的选项。"
type: docs
weight: 33
url: /zh/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

描述转换为 Presentation 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | 初始化 [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) 类的新实例。 |
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
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


初始化 [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) 类的新实例。


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
默认缩放在 Microsoft Powerpoint 2010 之前受支持。从 Microsoft Powerpoint 2013 开始，默认缩放不再设置为文档，而是似乎使用上一次打开的文档的缩放因子。


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


指定缩放比例（百分比）。默认值为 100。
默认缩放在 Microsoft Powerpoint 2010 之前受支持。从 Microsoft Powerpoint 2013 开始，默认缩放不再设置为文档，而是似乎使用上一次打开的文档的缩放因子。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

