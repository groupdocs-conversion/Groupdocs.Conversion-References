---
title: CadFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines CAD documents Computer Aided Design that are used for a 3D graphics file formats and may contain 2D or 3D designs.
type: docs
weight: 11
url: /java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

Defines CAD documents (Computer Aided Design) that are used for a 3D graphics file formats and may contain 2D or 3D designs. Includes the following types: [Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dgn), [Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwf), [Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwg), [Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwt), [Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dxf), [Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype\#Ifc), [Igs](../../com.groupdocs.conversion.filetypes/cadfiletype\#Igs), [Plt](../../com.groupdocs.conversion.filetypes/cadfiletype\#Plt), [Stl](../../com.groupdocs.conversion.filetypes/cadfiletype\#Stl). [Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype\#Cf2). [Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype\#Dwfx). Learn more about CAD formats [here][].


[here]: https://wiki.fileformat.com/cad
## Constructors

| Constructor | Description |
| --- | --- |
| [CadFileType()](#CadFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Dxf](#Dxf) | DXF, Drawing Interchange Format, or Drawing Exchange Format, is a tagged data representation of AutoCAD drawing file. |
| [Dwg](#Dwg) | DFiles with DWG extension represent proprietary binary files used for containing 2D and 3D design data. |
| [Dgn](#Dgn) | DGN, Design, files are drawings created by and supported by CAD applications such as MicroStation and Intergraph Interactive Graphics Design System. |
| [Dwf](#Dwf) | Design Web Format (DWF) represents 2D/3D drawing in compressed format for viewing, reviewing or printing design files. |
| [Stl](#Stl) | STL, abbreviation for stereolithrography, is an interchangeable file format that represents 3-dimensional surface geometry. |
| [Ifc](#Ifc) | Files with IFC extension refer to Industry Foundation Classes (IFC) file format that establishes international standards to import and export building objects and their properties. |
| [Plt](#Plt) | The PLT file format is a vector-based plotter file introduced by Autodesk, Inc. |
| [Igs](#Igs) | Igs document format |
| [Dwt](#Dwt) | A DWT file is an AutoCAD drawing template file that is used as starter for creating drawings that can be saved as DWG files. |
| [Dwfx](#Dwfx) | DWFX file is a 2D or 3D drawing created with Autodesk CAD software. |
| [Cf2](#Cf2) | Common File Format File. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Serialization constructor

### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF, Drawing Interchange Format, or Drawing Exchange Format, is a tagged data representation of AutoCAD drawing file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


DFiles with DWG extension represent proprietary binary files used for containing 2D and 3D design data. Like DXF, which are ASCII files, DWG represent the binary file format for CAD (Computer Aided Design) drawings. Learn more about this file format [here][]


[here]: https://wiki.fileformat.com/cad/dwg

### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN, Design, files are drawings created by and supported by CAD applications such as MicroStation and Intergraph Interactive Graphics Design System. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) represents 2D/3D drawing in compressed format for viewing, reviewing or printing design files. It contains graphics and text as part of design data and reduce the size of the file due to its compressed format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, abbreviation for stereolithrography, is an interchangeable file format that represents 3-dimensional surface geometry. The file format finds its usage in several fields such as rapid prototyping, 3D printing and computer-aided manufacturing. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/stl

### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


Files with IFC extension refer to Industry Foundation Classes (IFC) file format that establishes international standards to import and export building objects and their properties. This file format provides interoperability between different software applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### Plt {#Plt}
```
public static final CadFileType Plt
```


The PLT file format is a vector-based plotter file introduced by Autodesk, Inc. and contains information for a certain CAD file. Plotting details require accuracy and precision in production, and usage of PLT file guarantee this as all images are printed using lines instead of dots. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/plt

### Igs {#Igs}
```
public static final CadFileType Igs
```


Igs document format

### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


A DWT file is an AutoCAD drawing template file that is used as starter for creating drawings that can be saved as DWG files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


DWFX file is a 2D or 3D drawing created with Autodesk CAD software. It is saved in the DWFx format, which is similar to a . DWF file, but is formatted using Microsoft's XML Paper Specification (XPS).

### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Common File Format File. CAD file that contains 3D package designs or other model data; can be processed and cut by a CAD/CAM machine, such as a die cutting device.

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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
