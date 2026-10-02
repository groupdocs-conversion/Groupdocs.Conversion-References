---
title: "WatermarkTextOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات إعداد العلامة المائية النصية للمستند المحول"
type: docs
weight: 45
url: /ar/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

خيارات إعداد العلامة المائية النصية للمستند المحول

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | نص العلامة المائية |
|
|  | [setText(String value)](#setText-java.lang.String-) | نص العلامة المائية |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | خط العلامة المائية إذا تم تطبيق علامة مائية نصية |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | يحدد خط العلامة المائية إذا تم تطبيق علامة مائية نصية |
|
|  | [getColor()](#getColor--) | لون خط العلامة المائية إذا تم تطبيق علامة مائية نصية |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | لون خط العلامة المائية إذا تم تطبيق علامة مائية نصية |
|
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


نص العلامة المائية


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


نص العلامة المائية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


خط العلامة المائية إذا تم تطبيق علامة مائية نصية


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


يحدد خط العلامة المائية إذا تم تطبيق علامة مائية نصية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | خط |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


لون خط العلامة المائية إذا تم تطبيق علامة مائية نصية


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


لون خط العلامة المائية إذا تم تطبيق علامة مائية نصية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
