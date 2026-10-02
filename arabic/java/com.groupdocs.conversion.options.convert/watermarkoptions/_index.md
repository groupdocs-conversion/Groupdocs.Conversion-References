---
title: "WatermarkOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات إعداد العلامة المائية للمستند المحول"
type: docs
weight: 44
url: /ar/java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

خيارات إعداد العلامة المائية للمستند المحول

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WatermarkOptions()](#WatermarkOptions--) | إنشاء فئة WatermarkOptions وتعيين نص العلامة المائية |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | عرض العلامة المائية |
|
|  | [setWidth(int value)](#setWidth-int-) | عرض العلامة المائية |
|
|  | [getHeight()](#getHeight--) | ارتفاع العلامة المائية |
|
|  | [setHeight(int value)](#setHeight-int-) | ارتفاع العلامة المائية |
|
|  | [getTop()](#getTop--) | موضع العلامة المائية العلوي |
|
|  | [setTop(int value)](#setTop-int-) | موضع العلامة المائية العلوي |
|
|  | [getLeft()](#getLeft--) | موضع العلامة المائية الأيسر |
|
|  | [setLeft(int value)](#setLeft-int-) | موضع العلامة المائية الأيسر |
|
|  | [getRotationAngle()](#getRotationAngle--) | زاوية دوران العلامة المائية |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | زاوية دوران العلامة المائية |
|
|  | [getTransparency()](#getTransparency--) | شفافية العلامة المائية. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | شفافية العلامة المائية. |
|
|  | [getBackground()](#getBackground--) | يشير إلى أن العلامة المائية تم وضعها كخلفية. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | يشير إلى أن العلامة المائية تم وضعها كخلفية. |
|
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
|  | [deepClone()](#deepClone--) | استنساخ النسخة الحالية |
|
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


إنشاء فئة WatermarkOptions وتعيين نص العلامة المائية


### getWidth() {#getWidth--}
```
public final int getWidth()
```


عرض العلامة المائية


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


عرض العلامة المائية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ارتفاع العلامة المائية


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ارتفاع العلامة المائية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


موضع العلامة المائية العلوي


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


موضع العلامة المائية العلوي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


موضع العلامة المائية الأيسر


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


موضع العلامة المائية الأيسر


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


زاوية دوران العلامة المائية


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


زاوية دوران العلامة المائية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


شفافية العلامة المائية. القيمة بين 0 و 1. القيمة 0 تعني مرئية بالكامل، والقيمة 1 تعني غير مرئية.


**Returns:**
مزدوج
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


شفافية العلامة المائية. القيمة بين 0 و 1. القيمة 0 تعني مرئية بالكامل، والقيمة 1 تعني غير مرئية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | مزدوج |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


يشير إلى أن العلامة المائية تم وضعها كخلفية. إذا كانت القيمة true، توضع العلامة المائية في الأسفل. بشكل افتراضي تكون false وتوضع العلامة المائية في الأعلى.


**Returns:**
منطقي
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


يشير إلى أن العلامة المائية تم وضعها كخلفية. إذا كانت القيمة true، توضع العلامة المائية في الأسفل. بشكل افتراضي تكون false وتوضع العلامة المائية في الأعلى.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### isAutoAlign() {#isAutoAlign--}
```
public boolean isAutoAlign()
```




**Returns:**
منطقي
### setAutoAlign(boolean autoAlign) {#setAutoAlign-boolean-}
```
public void setAutoAlign(boolean autoAlign)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| autoAlign | منطقي |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


استنساخ النسخة الحالية


**Returns:**
java.lang.Object - نسخة

