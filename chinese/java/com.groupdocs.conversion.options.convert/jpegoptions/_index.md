---
title: "JpegOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "转换为 Jpeg 文件类型的选项。"
type: docs
weight: 20
url: /zh/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

转换为 Jpeg 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | 初始化 [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getQuality()](#getQuality--) | 期望的图像质量。 |
|
|  | [setQuality(int value)](#setQuality-int-) | 期望的图像质量。 |
|
|  | [getColorMode()](#getColorMode--) | Jpg 颜色模式。 |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Jpg 颜色模式。 |
|
|  | [getCompression()](#getCompression--) | Jpg 压缩方式。 |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Jpg 压缩方式。 |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


初始化 [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) 类的新实例。


### getQuality() {#getQuality--}
```
public final int getQuality()
```


期望的图像质量。该值必须在 0 到 100 之间。默认值为 100。


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


期望的图像质量。该值必须在 0 到 100 之间。默认值为 100。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Jpg 颜色模式。


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Jpg 颜色模式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Jpg 压缩方式。


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Jpg 压缩方式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

