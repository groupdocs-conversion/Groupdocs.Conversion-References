---
title: CadLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading CAD documents.
type: docs
weight: 10
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

