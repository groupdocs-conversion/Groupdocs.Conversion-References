---
title: "CadFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义用于 3D 图形文件格式的 CAD（Computer Aided Design）文档，可能包含 2D 或 3D 设计。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

定义 CAD 文档（计算机辅助设计），用于 3D 图形文件格式，可能包含 2D 或 3D 设计。
包括以下类型：
[Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype#Dgn),
[Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwf),
[Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwg),
[Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwt),
[Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dxf),
[Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype#Ifc),
[Igs](../../com.groupdocs.conversion.filetypes/cadfiletype#Igs),
[Plt](../../com.groupdocs.conversion.filetypes/cadfiletype#Plt),
[Stl](../../com.groupdocs.conversion.filetypes/cadfiletype#Stl).
[Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype#Cf2).
[Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwfx).
了解更多关于 CAD 格式的信息，请点击[此处](../https://wiki.fileformat.com/cad)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Dxf](#Dxf) | DXF（Drawing Interchange Format，或 Drawing Exchange Format）是一种针对 AutoCAD 绘图文件的标记数据表示。 |
|
|  | [Dwg](#Dwg) | 带有 DWG 扩展名的文件是用于包含 2D 和 3D 设计数据的专有二进制文件。 |
|
|  | [Dgn](#Dgn) | DGN（Design）文件是由 CAD 应用程序（如 MicroStation 和 Intergraph Interactive Graphics Design System）创建并支持的图纸。 |
|
|  | [Dwf](#Dwf) | Design Web Format（DWF）以压缩格式表示 2D/3D 绘图，用于查看、审阅或打印设计文件。 |
|
|  | [Stl](#Stl) | STL（stereolithrography 的缩写）是一种可互换的文件格式，表示三维表面几何。 |
|
|  | [Ifc](#Ifc) | 带有 IFC 扩展名的文件指的是 Industry Foundation Classes（IFC）文件格式，该格式建立了用于导入和导出建筑对象及其属性的国际标准。 |
|
|  | [Plt](#Plt) | PLT 文件格式是一种由 Autodesk, Inc. 推出的基于矢量的绘图仪文件。 |
|
|  | [Igs](#Igs) | Igs 文档格式 |
|
|  | [Dwt](#Dwt) | DWT 文件是 AutoCAD 绘图模板文件，用作创建可保存为 DWG 文件的绘图的起始模板。 |
|
|  | [Dwfx](#Dwfx) | DWFX 文件是使用 Autodesk CAD 软件创建的 2D 或 3D 绘图。 |
|
|  | [Cf2](#Cf2) | 通用文件格式文件。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


序列化构造函数


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF（Drawing Interchange Format，或 Drawing Exchange Format）是一种针对 AutoCAD 绘图文件的标记数据表示。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/cad/dxf)。


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


带有 DWG 扩展名的文件是用于包含 2D 和 3D 设计数据的专有二进制文件。与 DXF（ASCII 文件）不同，DWG 代表 CAD（Computer Aided Design）绘图的二进制文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/cad/dwg)。


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN（Design）文件是由 CAD 应用程序（如 MicroStation 和 Intergraph Interactive Graphics Design System）创建并支持的图纸。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/cad/dgn)。


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) 表示用于查看、审阅或打印设计文件的压缩格式的 2D/3D 图纸。它包含作为设计数据一部分的图形和文本，并由于其压缩格式而减小文件大小。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL 是立体光刻（stereolithrography）的缩写，是一种可互换的文件格式，用于表示三维表面几何。该文件格式在快速原型、3D 打印和计算机辅助制造等多个领域中得到应用。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


带有 IFC 扩展名的文件指的是 Industry Foundation Classes (IFC) 文件格式，该格式建立了用于导入和导出建筑对象及其属性的国际标准。此文件格式提供了不同软件应用之间的互操作性。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


PLT 文件格式是一种由 Autodesk, Inc. 推出的基于矢量的绘图仪文件，包含特定 CAD 文件的信息。绘图细节在生产中需要精确和准确，使用 PLT 文件能够保证这一点，因为所有图像都是使用线条而非点进行打印的。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Igs 文档格式


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


DWT 文件是 AutoCAD 绘图模板文件，用作创建可保存为 DWG 文件的绘图的起始模板。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


DWFX 文件是使用 Autodesk CAD 软件创建的 2D 或 3D 图纸。它以 DWFx 格式保存，该格式类似于 .DWF 文件，但使用 Microsoft 的 XML Paper Specification (XPS) 进行格式化。


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


通用文件格式文件。CAD 文件包含 3D 包装设计或其他模型数据；可由 CAD/CAM 机器（如模切设备）进行加工和切割。


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


为源文件类型准备了默认加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


为文件类型准备了默认转换选项


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
