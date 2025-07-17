---
title: ThreeDFileType
second_title: GroupDocs.Conversion for .NET API Reference
description: Defines 3D documents Includes the following types Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb Learn more about 3D formats herehttps//wiki.fileformat.com/3d.
type: docs
weight: 1140
url: /net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Defines 3D documents Includes the following types: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) Learn more about 3D formats [here](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serialization constructor |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | An AMF file consists of guidelines for objects description in order to be used by Additive Manufacturing processes. It contains an opening XML tag and ends with a element. This is preceded by an XML declaration line specifying the XML version and encoding of the file. Learn more about this file format [here](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | A file with a .ase extension is an Autodesk ASCII Scene Export file format that is an ASCII representation of a scene, containing 2D or 3D information while exporting scene data using Autodesk. Learn more about this file format [here](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | A DAE file is a Digital Asset Exchange file format that is used for exchanging data between interactive 3D applications. This file format is based on the COLLADA (COLLAborative Design Activity) XML schema which is an open standard XML schema for the exchange of digital assets among graphics software applications. Learn more about this file format [here](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | A file with .drc extension is a compressed 3D file format created with Google Draco library. Google offers Draco as open source library for compressing and decompressing 3D geometric meshes and point clouds, and improves storage and transmission of 3D graphics. Learn more about this file format [here](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, is a popular 3D file format that was originally developed by Kaydara for MotionBuilder. It was acquired by Autodesk Inc in 2006 and is now one of the main 3D exchange formats as used by many 3D tools. FBX is available in both binary and ASCII file format. Learn more about this file format [here](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB is the binary file format representation of 3D models saved in the GL Transmission Format (glTF). This binary format stores the glTF asset (JSON, .bin and images) in a binary blob. Learn more about this file format [here](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) is a 3D file format that stores 3D model information in JSON format. The use of JSON minimizes both the size of 3D assets and the runtime processing needed to unpack and use those assets. Learn more about this file format [here](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) is an efficient, industry-focused and flexible ISO-standardized 3D data format developed by Siemens PLM Software. Mechanical CAD domains of Aerospace, automotive industry, and Heavy Equipment use JT as their most leading 3D visualization format. Learn more about this file format [here](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | A file with .ma extension is a 3D project file created with Autodesk Maya application. It contains large list of textual commands to specify information about the file. Learn more about this file format [here](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | A file with .mb extension is a binary project file created with Autodesk Maya application. Unlike the MA file format, which is in ASCII file format, MB files are stored in binary file format. Learn more about this file format [here](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ files are used by Wavefront’s Advanced Visualizer application to define and store the geometric objects. Backward and forward transmission of geometric data is made possible through OBJ files. Learn more about this file format [here](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, represents 3D file format that stores graphical objects described as a collection of polygons. The purpose of this file format was to establish a simple and easy file type that is general enough to be useful for a wide range of models. Learn more about this file format [here](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM data files are related to AVEVA PDMS. RVM file is an AVEVA Plant Design Management System Model project file. AVEVA’s Plant Design Management System (PDMS) is the most popular 3D design system using data-centric technology for managing projects. Learn more about this file format [here](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | A file with .3ds extension represents 3D Sudio (DOS) mesh file format used by Autodesk 3D Studio. Autodesk 3D Studio has been in 3D file format market since 1990s and has now evolved to 3D Studio MAX for working with 3D modeling, animation and rendering. Learn more about this file format [here](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, is used by applications to render 3D object models to a variety of other applications, platforms, services and printers. It was built to avoid the limitations and issues in other 3D file formats, like STL, for working with the latest versions of 3D printers. Learn more about this file format [here](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) is a compressed file format and data structure for 3D computer graphics. It contains 3D model information such as triangle meshes, lighting, shading, motion data, lines and points with color and structure. Learn more about this file format [here](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | A file with .usd extension is a Universal Scene Description file format that encodes data for the purpose of data interchanging and augmenting between digital content creation applications. Developed by Pixar, USD provides the ability to interchange elemental assets (such as models) or animation. Learn more about this file format [here](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | A file with .usdz is an uncompressed and unencrypted ZIP archive for the USD (Universal Scene Description) file format that contains and proxies for files of other formats (such as textures, and animations) embedded within the archive and runs them directly with the USD run-time without any need of unpacking. Learn more about this file format [here](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | The Virtual Reality Modeling Language (VRML) is a file format for representation of interactive 3D world objects over the World Wide Web (www). It finds its usage in creating three-dimensional representations of complex scenes such as illustrations, definition and virtual reality presentations. Learn more about this file format [here](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | A file with .x extension refers to DirectX 3D Graphics legacy file format that was introduced with Microsoft DirectX 2.0. It was used for 3D graphics rendering in games and specifies the structures for meshes, textures, animations, and user-defined objects. It has been deprecated since 2014 as the Autodesk FBX file format serves better as a more modern format. Learn more about this file format [here](https://docs.fileformat.com/3d/x). |

### See Also

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
