---
title: WatermarkTextOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for settings text watermark to the converted document
type: docs
weight: 45
url: /java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Options for settings text watermark to the converted document
## Constructors

| Constructor | Description |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Watermark text |
| [setText(String value)](#setText-java.lang.String-) | Watermark text |
| [getWatermarkFont()](#getWatermarkFont--) | Watermark font if text watermark is applied |
| [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Sets Watermark font if text watermark is applied |
| [getColor()](#getColor--) | Watermark font color if text watermark is applied |
| [getColorInternal()](#getColorInternal--) |  |
| [setColor(Color value)](#setColor-java.awt.Color-) | Watermark font color if text watermark is applied |
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Watermark text

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Watermark text

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Watermark font if text watermark is applied

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font
### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Sets Watermark font if text watermark is applied

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | font |

### getColor() {#getColor--}
```
public final Color getColor()
```


Watermark font color if text watermark is applied

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


Watermark font color if text watermark is applied

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
