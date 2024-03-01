---
title: WatermarkOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for settings watermark to the converted document
type: docs
weight: 44
url: /nodejs-java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Options for settings watermark to the converted document
## Constructors

| Constructor | Description |
| --- | --- |
| [WatermarkOptions()](#WatermarkOptions--) | Create WatermarkOptions class and set watermark text |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Watermark width |
| [setWidth(int value)](#setWidth-int-) | Watermark width |
| [getHeight()](#getHeight--) | Watermark height |
| [setHeight(int value)](#setHeight-int-) | Watermark height |
| [getTop()](#getTop--) | Watermark top position |
| [setTop(int value)](#setTop-int-) | Watermark top position |
| [getLeft()](#getLeft--) | Watermark left position |
| [setLeft(int value)](#setLeft-int-) | Watermark left position |
| [getRotationAngle()](#getRotationAngle--) | Watermark rotation angle |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Watermark rotation angle |
| [getTransparency()](#getTransparency--) | Watermark transparency. |
| [setTransparency(double value)](#setTransparency-double-) | Watermark transparency. |
| [getBackground()](#getBackground--) | Indicates that the watermark is stamped as background. |
| [setBackground(boolean value)](#setBackground-boolean-) | Indicates that the watermark is stamped as background. |
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
| [deepClone()](#deepClone--) | Clone current instance |
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Create WatermarkOptions class and set watermark text

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Watermark width

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Watermark width

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Watermark height

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Watermark height

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Watermark top position

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Watermark top position

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Watermark left position

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Watermark left position

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Watermark rotation angle

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Watermark rotation angle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Watermark transparency. Value between 0 and 1. Value 0 is fully visible, value 1 is invisible.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Watermark transparency. Value between 0 and 1. Value 0 is fully visible, value 1 is invisible.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Indicates that the watermark is stamped as background. If the value is true, the watermark is laid at the bottom. By default is false and the watermark is laid on top.

**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Indicates that the watermark is stamped as background. If the value is true, the watermark is laid at the bottom. By default is false and the watermark is laid on top.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutoAlign() {#isAutoAlign--}
```
public boolean isAutoAlign()
```




**Returns:**
boolean
### setAutoAlign(boolean autoAlign) {#setAutoAlign-boolean-}
```
public void setAutoAlign(boolean autoAlign)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clone current instance

**Returns:**
java.lang.Object - instance
