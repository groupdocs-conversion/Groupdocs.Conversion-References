---
title: DiagramFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Diagram documents.
type: docs
weight: 13
url: /java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Defines Diagram documents. Includes the following types: [Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdw), [Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdx), [Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsd), [Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdm), [Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdx), [Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vss), [Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssm), [Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssx), [Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vst), [Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstm), [Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstx), [Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsx), [Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vtx).
## Constructors

| Constructor | Description |
| --- | --- |
| [DiagramFileType()](#DiagramFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Vsd](#Vsd) | VSD files are drawings created with Microsoft Visio application to represent variety of graphical objects and the interconnection between these. |
| [Vsdx](#Vsdx) | Files with .VSDX extension represent Microsoft Visio file format introduced from Microsoft Office 2013 onwards. |
| [Vss](#Vss) | VSS are stencil files created with Microsoft Visio 2007 and earlier. |
| [Vst](#Vst) | Files with VST extension are vector image files created with Microsoft Visio and act as template for creating further files. |
| [Vsx](#Vsx) | Files with .VSX extension refer to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. |
| [Vtx](#Vtx) | A file with VTX extension is a Microsoft Visio drawing template that is saved to disc in XML file format. |
| [Vdw](#Vdw) | VDW is the Visio Graphics Service file format that specifies the streams and storages required for rendering a Web drawing. |
| [Vdx](#Vdx) | Any drawing or chart created in Microsoft Visio, but saved in XML format have .VDX extension. |
| [Vssx](#Vssx) | Files with .VSSX extension are drawing stencils created with Microsoft Visio 2013 and above. |
| [Vstx](#Vstx) | Files with VSTX extensions are drawing template files created with Microsoft Visio 2013 and above. |
| [Vsdm](#Vsdm) | Files with VSDM extension are drawing files created with Microsoft Visio application that supports macros. |
| [Vssm](#Vssm) | Files with .VSSM extension are Microsoft Visio Stencil files that support provide support for macros. |
| [Vstm](#Vstm) | Files with VSTM extension are template files created with Microsoft Visio that support macros. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Serialization constructor

### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


VSD files are drawings created with Microsoft Visio application to represent variety of graphical objects and the interconnection between these. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsd

### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


Files with .VSDX extension represent Microsoft Visio file format introduced from Microsoft Office 2013 onwards. It was developed to replace the binary file format, .VSD, which is supported by earlier versions of Microsoft Visio. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS are stencil files created with Microsoft Visio 2007 and earlier. Stencil files provide drawing objects that can be included in a .VSD Visio drawing. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vss

### Vst {#Vst}
```
public static final DiagramFileType Vst
```


Files with VST extension are vector image files created with Microsoft Visio and act as template for creating further files. These template files are in binary file format and contain the default layout and settings that are utilized for creation of new Visio drawings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vst

### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


Files with .VSX extension refer to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. VSX files are saved in XML file format and was supported till Visio 2013. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsx

### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


A file with VTX extension is a Microsoft Visio drawing template that is saved to disc in XML file format. The template is aimed to provide a file with basic settings that can be used to create multiple Visio files of the same settings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vtx

### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW is the Visio Graphics Service file format that specifies the streams and storages required for rendering a Web drawing. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/vdw

### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Any drawing or chart created in Microsoft Visio, but saved in XML format have .VDX extension. A Visio drawing XML file is created in Visio software, which is developed by Microsoft. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vdx

### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


Files with .VSSX extension are drawing stencils created with Microsoft Visio 2013 and above. The VSSX file format can be opened with Visio 2013 and above. Visio files are known for representation of a variety of drawing elements such as collection of shapes, connectors, flowcharts, network layout, UML diagrams, Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vssx

### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


Files with VSTX extensions are drawing template files created with Microsoft Visio 2013 and above. These VSTX files provide starting point for creating Visio drawings, saved as .VSDX files, with default layout and settings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vstx

### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


Files with VSDM extension are drawing files created with Microsoft Visio application that supports macros. VSDM files are OPC/XML drawings that are similar to VSDX, but also provide the capability to run macros when the file is opened. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


Files with .VSSM extension are Microsoft Visio Stencil files that support provide support for macros. A VSSM file when opened allows to run the macros to achieve desired formatting and placement of shapes in a diagram. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vssm

### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


Files with VSTM extension are template files created with Microsoft Visio that support macros. Unlike VSDX files, files created from VSTM templates can run macros that are developed in Visual Basic for Applications (VBA) code. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vstm

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
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
