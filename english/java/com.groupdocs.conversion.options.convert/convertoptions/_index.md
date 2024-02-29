---
title: ConvertOptions
second_title: GroupDocs.Conversion for Java API Reference
description: The general conversion options class.
type: docs
weight: 12
url: /java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

The general conversion options class.
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | \{@inheritDoc\} |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | The desired file type the input document should be converted to. |
| [deepClone()](#deepClone--) | Clones current options instance. |
| [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | The desired file type the input document should be converted to. |
| [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | The desired file type the input document should be converted to. |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Gets the desired file type the input document should be converted to.

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


The desired file type the input document should be converted to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clones current options instance.

**Returns:**
java.lang.Object - 
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


The desired file type the input document should be converted to.

**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


The desired file type the input document should be converted to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | TFileType |  |

