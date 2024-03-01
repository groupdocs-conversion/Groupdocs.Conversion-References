---
title: TargetConversion
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Represents possible target conversion and a flag is it a primary or secondary
type: docs
weight: 14
url: /nodejs-java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Represents possible target conversion and a flag is it a primary or secondary
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Target document format |
| [isPrimary()](#isPrimary--) | Is the conversion primary |
| [getConvertOptions()](#getConvertOptions--) | Predefined convert options which could be used to convert to current type |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Target document format

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Is the conversion primary

**Returns:**
boolean - `true` if primary
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Predefined convert options which could be used to convert to current type

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options
