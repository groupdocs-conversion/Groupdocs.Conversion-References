---
title: "JpegOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع ملف Jpeg."
type: docs
weight: 20
url: /ar/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

خيارات التحويل إلى نوع ملف Jpeg.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | يُنشئ مثيلًا جديدًا من الفئة [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getQuality()](#getQuality--) | جودة الصورة المطلوبة. |
|
|  | [setQuality(int value)](#setQuality-int-) | جودة الصورة المطلوبة. |
|
|  | [getColorMode()](#getColorMode--) | وضع اللون Jpg. |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | وضع اللون Jpg. |
|
|  | [getCompression()](#getCompression--) | طريقة ضغط Jpg. |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | طريقة ضغط Jpg. |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


يُنشئ مثيلًا جديدًا من الفئة [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions).


### getQuality() {#getQuality--}
```
public final int getQuality()
```


جودة الصورة المطلوبة. يجب أن تكون القيمة بين 0 و 100. القيمة الافتراضية هي 100.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


جودة الصورة المطلوبة. يجب أن تكون القيمة بين 0 و 100. القيمة الافتراضية هي 100.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


وضع اللون Jpg.


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


وضع اللون Jpg.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


طريقة ضغط Jpg.


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


طريقة ضغط Jpg.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

