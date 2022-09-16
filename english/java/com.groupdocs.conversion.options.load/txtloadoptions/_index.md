---
title: TxtLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading Txt documents.
type: docs
weight: 32
url: /java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Options for loading Txt documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [TxtLoadOptions()](#TxtLoadOptions--) | Initializes new instance of [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Allows to specify how numbered list items are recognized when plain text document is converted. |
| [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Allows to specify how numbered list items are recognized when plain text document is converted. |
| [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Gets or sets preferred option of a trailing space handling. |
| [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Gets or sets preferred option of a trailing space handling. |
| [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Gets or sets preferred option of a leading space handling. |
| [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Gets or sets preferred option of a leading space handling. |
| [getEncoding()](#getEncoding--) | Gets or sets the encoding that will be used when loading Txt document. |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Gets or sets the encoding that will be used when loading Txt document. |
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Initializes new instance of [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) class.

### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Input document file type

**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Allows to specify how numbered list items are recognized when plain text document is converted. The default value is true.

--------------------

If this option is set to false, lists recognition algorithm detects list paragraphs, when list numbers ends with either dot, right bracket or bullet symbols (such as "\\u2022", "\*", "-" or "o").

If this option is set to true, whitespaces are also used as list number delimiters: list recognition algorithm for Arabic style numbering (1., 1.1.2.) uses both whitespaces and dot (".") symbols.

**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Allows to specify how numbered list items are recognized when plain text document is converted. The default value is true.

--------------------

If this option is set to false, lists recognition algorithm detects list paragraphs, when list numbers ends with either dot, right bracket or bullet symbols (such as "\\u2022", "\*", "-" or "o").

If this option is set to true, whitespaces are also used as list number delimiters: list recognition algorithm for Arabic style numbering (1., 1.1.2.) uses both whitespaces and dot (".") symbols.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Gets or sets preferred option of a trailing space handling. Default value is [TxtTrailingSpacesOptions\#Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\#Trim).

**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Gets or sets preferred option of a trailing space handling. Default value is [TxtTrailingSpacesOptions\#Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\#Trim).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Gets or sets preferred option of a leading space handling. Default value is [TxtLeadingSpacesOptions\#ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\#ConvertToIndent).

**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Gets or sets preferred option of a leading space handling. Default value is [TxtLeadingSpacesOptions\#ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\#ConvertToIndent).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Gets or sets the encoding that will be used when loading Txt document. Can be null. Default is null.

**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Gets or sets the encoding that will be used when loading Txt document. Can be null. Default is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

