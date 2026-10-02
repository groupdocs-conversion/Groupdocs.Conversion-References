---
title: "WatermarkOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "用于在转换后的文档中设置水印的选项"
type: docs
weight: 44
url: /zh/java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

用于在转换后的文档中设置水印的选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WatermarkOptions()](#WatermarkOptions--) | 创建 WatermarkOptions 类并设置水印文本 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 水印宽度 |
|
|  | [setWidth(int value)](#setWidth-int-) | 水印宽度 |
|
|  | [getHeight()](#getHeight--) | 水印高度 |
|
|  | [setHeight(int value)](#setHeight-int-) | 水印高度 |
|
|  | [getTop()](#getTop--) | 水印顶部位置 |
|
|  | [setTop(int value)](#setTop-int-) | 水印顶部位置 |
|
|  | [getLeft()](#getLeft--) | 水印左侧位置 |
|
|  | [setLeft(int value)](#setLeft-int-) | 水印左侧位置 |
|
|  | [getRotationAngle()](#getRotationAngle--) | 水印旋转角度 |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | 水印旋转角度 |
|
|  | [getTransparency()](#getTransparency--) | 水印透明度。 |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 水印透明度。 |
|
|  | [getBackground()](#getBackground--) | 指示水印被标记为背景。 |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | 指示水印被标记为背景。 |
|
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
|  | [deepClone()](#deepClone--) | 克隆当前实例 |
|
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


创建 WatermarkOptions 类并设置水印文本


### getWidth() {#getWidth--}
```
public final int getWidth()
```


水印宽度


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


水印宽度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


水印高度


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


水印高度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


水印顶部位置


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


水印顶部位置


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


水印左侧位置


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


水印左侧位置


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


水印旋转角度


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


水印旋转角度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


水印透明度。值在 0 到 1 之间。值 0 表示完全可见，值 1 表示不可见。


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


水印透明度。值在 0 到 1 之间。值 0 表示完全可见，值 1 表示不可见。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


指示水印被标记为背景。如果该值为 true，水印放置在底部。默认情况下为 false，水印放置在顶部。


**Returns:**
布尔
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


指示水印被标记为背景。如果该值为 true，水印放置在底部。默认情况下为 false，水印放置在顶部。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### isAutoAlign() {#isAutoAlign--}
```
public boolean isAutoAlign()
```




**Returns:**
布尔
### setAutoAlign(boolean autoAlign) {#setAutoAlign-boolean-}
```
public void setAutoAlign(boolean autoAlign)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| autoAlign | 布尔 |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


克隆当前实例


**Returns:**
java.lang.Object - instance

