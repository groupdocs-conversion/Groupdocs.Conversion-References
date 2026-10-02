---
title: "WatermarkTextOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "用于在转换后的文档中设置文字水印的选项"
type: docs
weight: 45
url: /zh/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

用于在转换后的文档中设置文字水印的选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getText()](#getText--) | 水印文本 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 水印文本 |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | 如果应用文本水印，则使用的水印字体 |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | 设置文本水印时使用的水印字体 |
|
|  | [getColor()](#getColor--) | 如果应用文本水印，则使用的水印字体颜色 |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 如果应用文本水印，则使用的水印字体颜色 |
|
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


水印文本


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


水印文本


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


如果应用文本水印，则使用的水印字体


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


设置文本水印时使用的水印字体


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | 字体 |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


如果应用文本水印，则使用的水印字体颜色


**Returns:**
java.awt.Color
### getColorInternal() {#getColorInternal--}
```
public System.Drawing.Color getColorInternal()
```




**Returns:**
com.aspose.ms.System.Drawing.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


如果应用文本水印，则使用的水印字体颜色


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
