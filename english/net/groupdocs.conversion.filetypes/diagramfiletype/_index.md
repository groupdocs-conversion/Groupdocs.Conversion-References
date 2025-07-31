---
title: DiagramFileType
second_title: GroupDocs.Conversion for .NET API Reference
description: Defines Diagram documents. Includes the following types Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx.
type: docs
weight: 990
url: /net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Defines Diagram documents. Includes the following types: [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Constructors

| Name | Description |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Serialization constructor |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | File type description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | The file extension |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | The file family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | The file format |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compares current object to other. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implements [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Serves as the default hash function. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String representation |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW is the Visio Graphics Service file format that specifies the streams and storages required for rendering a Web drawing. Learn more about this file format [here](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Any drawing or chart created in Microsoft Visio, but saved in XML format have .VDX extension. A Visio drawing XML file is created in Visio software, which is developed by Microsoft. Learn more about this file format [here](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD files are drawings created with Microsoft Visio application to represent variety of graphical objects and the interconnection between these. Learn more about this file format [here](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Files with VSDM extension are drawing files created with Microsoft Visio application that supports macros. VSDM files are OPC/XML drawings that are similar to VSDX, but also provide the capability to run macros when the file is opened. Learn more about this file format [here](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Files with .VSDX extension represent Microsoft Visio file format introduced from Microsoft Office 2013 onwards. It was developed to replace the binary file format, .VSD, which is supported by earlier versions of Microsoft Visio. Learn more about this file format [here](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS are stencil files created with Microsoft Visio 2007 and earlier. Stencil files provide drawing objects that can be included in a .VSD Visio drawing. Learn more about this file format [here](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Files with .VSSM extension are Microsoft Visio Stencil files that support provide support for macros. A VSSM file when opened allows to run the macros to achieve desired formatting and placement of shapes in a diagram. Learn more about this file format [here](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Files with .VSSX extension are drawing stencils created with Microsoft Visio 2013 and above. The VSSX file format can be opened with Visio 2013 and above. Visio files are known for representation of a variety of drawing elements such as collection of shapes, connectors, flowcharts, network layout, UML diagrams, Learn more about this file format [here](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Files with VST extension are vector image files created with Microsoft Visio and act as template for creating further files. These template files are in binary file format and contain the default layout and settings that are utilized for creation of new Visio drawings. Learn more about this file format [here](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Files with VSTM extension are template files created with Microsoft Visio that support macros. Unlike VSDX files, files created from VSTM templates can run macros that are developed in Visual Basic for Applications (VBA) code. Learn more about this file format [here](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Files with VSTX extensions are drawing template files created with Microsoft Visio 2013 and above. These VSTX files provide starting point for creating Visio drawings, saved as .VSDX files, with default layout and settings. Learn more about this file format [here](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Files with .VSX extension refer to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. VSX files are saved in XML file format and was supported till Visio 2013. Learn more about this file format [here](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | A file with VTX extension is a Microsoft Visio drawing template that is saved to disc in XML file format. The template is aimed to provide a file with basic settings that can be used to create multiple Visio files of the same settings. Learn more about this file format [here](https://wiki.fileformat.com/image/vtx). |

### See Also

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
