---
title: IConvertOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Represents convert options
type: docs
weight: 48
url: /java/com.groupdocs.conversion.options.convert/iconvertoptions/
---```
public interface IConvertOptions
```

Represents convert options
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Gets the desired file type the input document should be converted to. |
| [setFormat(FileType format)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Sets the desired file type the input document should be converted to. |
### getFormat() {#getFormat--}
```
public abstract FileType getFormat()
```


Gets the desired file type the input document should be converted to.

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The desired file type the input document should be converted to.
### setFormat(FileType format) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public abstract void setFormat(FileType format)
```


Sets the desired file type the input document should be converted to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | file type |

