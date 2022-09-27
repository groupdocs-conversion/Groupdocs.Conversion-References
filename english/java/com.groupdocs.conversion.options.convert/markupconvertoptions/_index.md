---
title: MarkupConvertOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for conversion to Markup file type.
type: docs
weight: 23
url: /java/com.groupdocs.conversion.options.convert/markupconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class MarkupConvertOptions extends CommonConvertOptions<MarkupFileType> implements Serializable
```

Options for conversion to Markup file type.
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkupConvertOptions()](#MarkupConvertOptions--) | Initializes new instance of [MarkupConvertOptions](../../com.groupdocs.conversion.options.convert/markupconvertoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getUsePdf()](#getUsePdf--) | If  true , the input firstly is converted to PDF and after that to desired format |
| [setUsePdf(boolean value)](#setUsePdf-boolean-) | If  true , the input firstly is converted to PDF and after that to desired format |
| [getFixedLayout()](#getFixedLayout--) | If  true  fixed layout will be used e.g. |
| [setFixedLayout(boolean value)](#setFixedLayout-boolean-) | If  true  fixed layout will be used e.g. |
| [getZoom()](#getZoom--) | Specifies the zoom level in percentage. |
| [setZoom(int value)](#setZoom-int-) | Specifies the zoom level in percentage. |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) | Gets show page borders when converting to fixed layout flag. |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) | Show show page borders when converting to fixed layout flag. |
### MarkupConvertOptions() {#MarkupConvertOptions--}
```
public MarkupConvertOptions()
```


Initializes new instance of [MarkupConvertOptions](../../com.groupdocs.conversion.options.convert/markupconvertoptions) class.

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


If  true , the input firstly is converted to PDF and after that to desired format

**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


If  true , the input firstly is converted to PDF and after that to desired format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFixedLayout() {#getFixedLayout--}
```
public final boolean getFixedLayout()
```


If  true  fixed layout will be used e.g. absolutely positioned html elements Default: true

**Returns:**
boolean
### setFixedLayout(boolean value) {#setFixedLayout-boolean-}
```
public final void setFixedLayout(boolean value)
```


If  true  fixed layout will be used e.g. absolutely positioned html elements Default: true

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specifies the zoom level in percentage. Default is 100.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specifies the zoom level in percentage. Default is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```


Gets show page borders when converting to fixed layout flag. Default is True.

**Returns:**
boolean - true if show page borders
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```


Show show page borders when converting to fixed layout flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fixedLayoutShowBorders | boolean | show page borders |

