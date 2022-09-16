---
title: ThreeDFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines 3D documents Includes the following types  Learn more about 3D formats here.
type: docs
weight: 23
url: /java/com.groupdocs.conversion.filetypes/threedfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class ThreeDFileType extends FileType
```

Defines 3D documents Includes the following types:  Learn more about 3D formats [here][].


[here]: https://wiki.fileformat.com/3d
## Constructors

| Constructor | Description |
| --- | --- |
| [ThreeDFileType()](#ThreeDFileType--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Fbx](#Fbx) | FBX, FilmBox, is a popular 3D file format that was originally developed by Kaydara for MotionBuilder. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ThreeDFileType() {#ThreeDFileType--}
```
public ThreeDFileType()
```


### Fbx {#Fbx}
```
public static final ThreeDFileType Fbx
```


FBX, FilmBox, is a popular 3D file format that was originally developed by Kaydara for MotionBuilder. It was acquired by Autodesk Inc in 2006 and is now one of the main 3D exchange formats as used by many 3D tools. FBX is available in both binary and ASCII file format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/3d/fbx

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Prepared default load options for the source file type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Prepared default convert options for the file type

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
