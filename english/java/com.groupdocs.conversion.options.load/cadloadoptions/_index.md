---
title: CadLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading CAD documents.
type: docs
weight: 12
url: /java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

Options for loading CAD documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [CadLoadOptions()](#CadLoadOptions--) | Initializes new instance of [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getWidth()](#getWidth--) | Sets desired page width for converting CAD document |
| [setWidth(int value)](#setWidth-int-) | Sets desired page width for converting CAD document |
| [getHeight()](#getHeight--) | Sets desired page height for converting CAD document |
| [setHeight(int value)](#setHeight-int-) | Sets desired page height for converting CAD document |
| [getLayoutNames()](#getLayoutNames--) | Specifies which CAD layouts to be converted |
| [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Specififies which CAD layouts to be converted |
| [getDrawType()](#getDrawType--) | Gets type of drawing. |
| [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Sets type of drawing. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets a background color. |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Sets a background color. |
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Initializes new instance of [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) class.

### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Input document file type

**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Sets desired page width for converting CAD document

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sets desired page width for converting CAD document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Sets desired page height for converting CAD document

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sets desired page height for converting CAD document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Specifies which CAD layouts to be converted

**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Specififies which CAD layouts to be converted

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Gets type of drawing.

**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Sets type of drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Gets a background color.

**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Sets a background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

