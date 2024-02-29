---
title: Font
second_title: GroupDocs.Conversion for Java API Reference
description: Font settings
type: docs
weight: 16
url: /java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Font settings
## Constructors

| Constructor | Description |
| --- | --- |
| [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | creates new Font instance |
## Methods

| Method | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Fets font family name |
| [getSize()](#getSize--) | Gets font size |
| [isBold()](#isBold--) | Font bold flag |
| [setBold(boolean bold)](#setBold-boolean-) | Sets Font bold flag |
| [isItalic()](#isItalic--) | Font italic flag |
| [setItalic(boolean italic)](#setItalic-boolean-) | Sets font italic flag |
| [isUnderline()](#isUnderline--) | Gets Font underline |
| [setUnderline(boolean underline)](#setUnderline-boolean-) | Sets Font underline |
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


creates new Font instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Font name |
| size | float | Font size |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Fets font family name

**Returns:**
java.lang.String - Font family name
### getSize() {#getSize--}
```
public float getSize()
```


Gets font size

**Returns:**
float - Font size
### isBold() {#isBold--}
```
public boolean isBold()
```


Font bold flag

**Returns:**
boolean - true if bold
### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Sets Font bold flag

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bold | boolean | true if bold |

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Font italic flag

**Returns:**
boolean - true if Italic
### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Sets font italic flag

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| italic | boolean | true if Italic |

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Gets Font underline

**Returns:**
boolean - true if Font is underline
### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Sets Font underline

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| underline | boolean | Font underline flag |

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
| Parameter | Type | Description |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
