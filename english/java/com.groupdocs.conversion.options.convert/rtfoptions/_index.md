---
title: RtfOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for conversion to RTF file type.
type: docs
weight: 39
url: /java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

Options for conversion to RTF file type.
## Constructors

| Constructor | Description |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | Specifies whether the keywords for "old readers" are written to RTF or not. |
| [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | Specifies whether the keywords for "old readers" are written to RTF or not. |
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


Specifies whether the keywords for "old readers" are written to RTF or not. This can significantly affect the size of the RTF document. Default is False.

**Returns:**
boolean
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


Specifies whether the keywords for "old readers" are written to RTF or not. This can significantly affect the size of the RTF document. Default is False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

