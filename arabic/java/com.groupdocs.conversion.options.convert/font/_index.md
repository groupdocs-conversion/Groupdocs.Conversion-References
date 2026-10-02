---
title: "الخط"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "إعدادات الخط"
type: docs
weight: 16
url: /ar/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

إعدادات الخط

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | ينشئ كائن Font جديد |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | يحصل على اسم عائلة الخط |
|
|  | [getSize()](#getSize--) | يحصل على حجم الخط |
|
|  | [isBold()](#isBold--) | علامة الخط العريض |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | يضبط علامة الخط العريض |
|
|  | [isItalic()](#isItalic--) | علامة الخط المائل |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | يضبط علامة الخط المائل |
|
|  | [isUnderline()](#isUnderline--) | يحصل على تسطير الخط |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | يضبط تسطير الخط |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


ينشئ كائن Font جديد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | اسم الخط |
|
|  | size | float | حجم الخط |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


يحصل على اسم عائلة الخط


**Returns:**
java.lang.String - اسم عائلة الخط

### getSize() {#getSize--}
```
public float getSize()
```


يحصل على حجم الخط


**Returns:**
float - حجم الخط

### isBold() {#isBold--}
```
public boolean isBold()
```


علامة الخط العريض


**Returns:**
boolean - صحيح إذا كان غامقًا

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


يضبط علامة الخط العريض


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | غامق | منطقي | صحيح إذا كان غامقًا |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


علامة الخط المائل


**Returns:**
boolean - صحيح إذا كان مائلًا

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


يضبط علامة الخط المائل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مائل | منطقي | صحيح إذا كان مائلًا |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


يحصل على تسطير الخط


**Returns:**
boolean - صحيح إذا كان الخط مسطرًا

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


يضبط تسطير الخط


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسطر | منطقي | علامة تسطير الخط |
|

### getDefault() {#getDefault--}
```
public static Font getDefault()
```




**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
### clone(float newSize) {#clone-float-}
```
public Font clone(float newSize)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
