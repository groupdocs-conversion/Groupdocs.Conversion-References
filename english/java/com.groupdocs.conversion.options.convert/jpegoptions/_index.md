---
title: JpegOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for conversion to Jpeg file type.
type: docs
weight: 20
url: /java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Options for conversion to Jpeg file type.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initializes new instance of [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getQuality()](#getQuality--) | Desired image quality. |
| [setQuality(int value)](#setQuality-int-) | Desired image quality. |
| [getColorMode()](#getColorMode--) | Jpg color mode. |
| [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Jpg color mode. |
| [getCompression()](#getCompression--) | Jpg compression method. |
| [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Jpg compression method. |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initializes new instance of [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) class.

### getQuality() {#getQuality--}
```
public final int getQuality()
```


Desired image quality. The value must be between 0 and 100. The default value is 100.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Desired image quality. The value must be between 0 and 100. The default value is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Jpg color mode.

**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Jpg color mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Jpg compression method.

**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Jpg compression method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

