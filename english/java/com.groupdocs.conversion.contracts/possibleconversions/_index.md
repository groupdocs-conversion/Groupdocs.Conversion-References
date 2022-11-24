---
title: PossibleConversions
second_title: GroupDocs.Conversion for Java API Reference
description: Represents a mapping what conversion pairs are supported for specific source file format
type: docs
weight: 13
url: /java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Represents a mapping what conversion pairs are supported for specific source file format
## Constructors

| Constructor | Description |
| --- | --- |
| [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Creates possible conversion list for specified source file format |
## Fields

| Field | Description |
| --- | --- |
| [NULL](#NULL) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) | Predefined load options which could be used to convert from current type |
| [getAll()](#getAll--) | All target file types and primary/secondary flag |
| [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Returns target conversion for specified target file type |
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
| [getPrimary()](#getPrimary--) | Primary target file types |
| [getSecondary()](#getSecondary--) | Secondary target file types |
| [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Add conversion pair |
| [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Find conversion pair in current list for target file type |
| [getSource()](#getSource--) | Source file formats |
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Creates possible conversion list for specified source file format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | source file type |

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Predefined load options which could be used to convert from current type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options
### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


All target file types and primary/secondary flag

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Iterable of [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Returns target conversion for specified target file type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | target file type |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions
### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Primary target file types

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - primary target file types
### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Secondary target file types

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - secondary target file types
### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Add conversion pair

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | conversion pair |

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Find conversion pair in current list for target file type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | target file type |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair
### getSource() {#getSource--}
```
public FileType getSource()
```


Source file formats

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats
