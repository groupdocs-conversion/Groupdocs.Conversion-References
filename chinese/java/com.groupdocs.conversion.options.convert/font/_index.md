---
title: "字体"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "字体设置"
type: docs
weight: 16
url: /zh/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

字体设置

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | 创建新的 Font 实例 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | 获取字体族名称 |
|
|  | [getSize()](#getSize--) | 获取字体大小 |
|
|  | [isBold()](#isBold--) | Font 粗体标志 |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | 设置 Font 粗体标志 |
|
|  | [isItalic()](#isItalic--) | Font 斜体标志 |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | 设置字体斜体标志 |
|
|  | [isUnderline()](#isUnderline--) | 获取 Font 下划线 |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | 设置 Font 下划线 |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


创建新的 Font 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | 字体名称 |
|
|  | 大小 | float | 字体大小 |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


获取字体族名称


**Returns:**
java.lang.String - 字体族名称

### getSize() {#getSize--}
```
public float getSize()
```


获取字体大小


**Returns:**
float - 字体大小

### isBold() {#isBold--}
```
public boolean isBold()
```


Font 粗体标志


**Returns:**
boolean - 如果加粗则为 true

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


设置 Font 粗体标志


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 加粗 | 布尔 | 如果加粗则为 true |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Font 斜体标志


**Returns:**
boolean - 如果 Italic 则为 true

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


设置字体斜体标志


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 斜体 | 布尔 | 如果 Italic 则为 true |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


获取 Font 下划线


**Returns:**
boolean - 如果 Font 为下划线则为 true

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


设置 Font 下划线


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 下划线 | 布尔 | 字体下划线标志 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
