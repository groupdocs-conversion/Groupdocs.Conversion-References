---
title: CadFileType class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.filetypes/cadfiletype/
is_root: false
weight: 10
---

## CadFileType class

Defines CAD documents (Computer Aided Design) that are used for a 3D graphics file formats and may contain 2D or 3D designs.
Includes the following types:
[`CadFileType.Cf2`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype)[`CadFileType.Dgn`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype),
[`CadFileType.Dwf`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype),
[`CadFileType.Dwfx`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype)[`CadFileType.Dwg`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype),
[`CadFileType.Dwt`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype),
[`CadFileType.Dxf`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype),
[`CadFileType.Ifc`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype),
[`CadFileType.Igs`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype),
[`CadFileType.Plt`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype),
[`CadFileType.Stl`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype).
Learn more about CAD formats [here](https://wiki.fileformat.com/cad).



**Inheritance:** [`CadFileType`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype) → 
[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype) → 
[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)



The CadFileType type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/__init__/#) | Serialization constructor |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/file_format) | The file format |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/extension) | The file extension |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/family) | The file family |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/description) | File type description |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/unknown) | Unknown file type |
| [DXF](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, or Drawing Exchange Format, is a tagged data representation of AutoCAD drawing file.<br/>Learn more about this file format [here](https://wiki.fileformat.com/cad/dxf). |
| [DWG](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwg) | Files with DWG extension represent proprietary binary files used for containing 2D and 3D design data. Like DXF, which are ASCII files, DWG represent the binary file format for CAD (Computer Aided Design) drawings. <br/>Learn more about this file format [here](https://wiki.fileformat.com/cad/dwg). |
| [DGN](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, files are drawings created by and supported by CAD applications such as MicroStation and Intergraph Interactive Graphics Design System.<br/>Learn more about this file format [here](https://wiki.fileformat.com/cad/dgn). |
| [DWF](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) represents 2D/3D drawing in compressed format for viewing, reviewing or printing design files. It contains graphics and text as part of design data and reduce the size of the file due to its compressed format.<br/>Learn more about this file format [here](https://wiki.fileformat.com/cad/dwf). |
| [STL](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/stl) | STL, abbreviation for stereolithrography, is an interchangeable file format that represents 3-dimensional surface geometry. The file format finds its usage in several fields such as rapid prototyping, 3D printing and computer-aided manufacturing.<br/>Learn more about this file format [here](https://wiki.fileformat.com/cad/stl). |
| [IFC](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/ifc) | Files with IFC extension refer to  Industry Foundation Classes (IFC) file format that establishes international standards to import and export building objects and their properties. This file format provides interoperability between different software applications. <br/>Learn more about this file format [here](https://wiki.fileformat.com/cad/ifc). |
| [PLT](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/plt) | The PLT file format is a vector-based plotter file introduced by Autodesk, Inc. and contains information for a certain CAD file. Plotting details require accuracy and precision in production, and usage of PLT file guarantee this as all images are printed using lines instead of dots. <br/>Learn more about this file format [here](https://wiki.fileformat.com/cad/plt). |
| [IGS](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/igs) | Igs document format |
| [DWT](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwt) | A DWT file is an AutoCAD drawing template file that is used as starter for creating drawings that can be saved as DWG files.<br/>Learn more about this file format [here](https://wiki.fileformat.com/cad/dwt). |
| [DWFX](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX file is a 2D or 3D drawing created with Autodesk CAD software. It is saved in the DWFx format, which is similar to a . DWF file, but is formatted using Microsoft's XML Paper Specification (XPS). |
| [CF2](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/cf2) | Common File Format File. CAD file that contains 3D package designs or other model data; can be processed and cut by a CAD/CAM machine, such as a die cutting device. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/equals/#groupdocs.conversion.contracts.Enumeration) | Implements [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals) |
| [compare_to](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/compare_to/#System.Object) | Compares current object to other. |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/from_filename/#System.String) | Returns FileType for specified fileName |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/from_extension/#System.String) | Gets FileType for provided fileExtension |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/from_stream/#io.RawIOBase) | Returns FileType for provided document stream |



### See Also
* module [`groupdocs.conversion.filetypes`](..)
* class [`CadFileType`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype)
* class [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)
* class [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype)
