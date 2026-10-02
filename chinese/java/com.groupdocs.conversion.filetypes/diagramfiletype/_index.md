---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义图表文档。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

定义 Diagram 文档。包括以下类型：
[Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdw),
[Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdx),
[Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsd),
[Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdm),
[Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdx),
[Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vss),
[Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssm),
[Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssx),
[Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vst),
[Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstm),
[Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstx),
[Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsx),
[Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vtx).

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Vsd](#Vsd) | VSD 文件是使用 Microsoft Visio 应用程序创建的图形，用于表示各种图形对象及其相互连接。 |
|
|  | [Vsdx](#Vsdx) | .VSDX 扩展名的文件代表自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。 |
|
|  | [Vss](#Vss) | VSS 是使用 Microsoft Visio 2007 及更早版本创建的模板文件。 |
|
|  | [Vst](#Vst) | 带有 VST 扩展名的文件是使用 Microsoft Visio 创建的矢量图像文件，并充当用于创建后续文件的模板。 |
|
|  | [Vsx](#Vsx) | 带有 .VSX 扩展名的文件指的是由绘图和形状组成的模板，用于在 Microsoft Visio 中创建图表。 |
|
|  | [Vtx](#Vtx) | 带有 VTX 扩展名的文件是以 XML 文件格式保存到磁盘的 Microsoft Visio 绘图模板。 |
|
|  | [Vdw](#Vdw) | VDW 是 Visio Graphics Service 文件格式，指定渲染 Web 绘图所需的流和存储。 |
|
|  | [Vdx](#Vdx) | 在 Microsoft Visio 中创建的任何绘图或图表，如果以 XML 格式保存，则具有 .VDX 扩展名。 |
|
|  | [Vssx](#Vssx) | 带有 .VSSX 扩展名的文件是使用 Microsoft Visio 2013 及以上版本创建的绘图模板。 |
|
|  | [Vstx](#Vstx) | 带有 VSTX 扩展名的文件是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。 |
|
|  | [Vsdm](#Vsdm) | 带有 VSDM 扩展名的文件是由支持宏的 Microsoft Visio 应用程序创建的绘图文件。 |
|
|  | [Vssm](#Vssm) | 带有 .VSSM 扩展名的文件是支持宏的 Microsoft Visio 模板文件。 |
|
|  | [Vstm](#Vstm) | 带有 VSTM 扩展名的文件是由支持宏的 Microsoft Visio 创建的模板文件。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


序列化构造函数


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


VSD 文件是使用 Microsoft Visio 应用程序创建的图形，用于表示各种图形对象及其相互连接。
了解更多关于此文件格式的信息 [here](../https://wiki.fileformat.com/image/vsd)。


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


带有 .VSDX 扩展名的文件代表自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。它的开发是为了取代二进制文件格式 .VSD，该格式受早期版本的 Microsoft Visio 支持。
了解更多关于此文件格式的信息 [here](../https://wiki.fileformat.com/image/vsdx)。


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS 是使用 Microsoft Visio 2007 及更早版本创建的模板文件。模板文件提供可包含在 .VSD Visio 绘图中的绘图对象。
了解更多关于此文件格式的信息 [here](../https://wiki.fileformat.com/image/vss)。


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


带有 VST 扩展名的文件是使用 Microsoft Visio 创建的矢量图像文件，并充当用于创建后续文件的模板。这些模板文件采用二进制文件格式，包含用于创建新 Visio 绘图的默认布局和设置。
了解更多关于此文件格式的信息 [here](../https://wiki.fileformat.com/image/vst)。


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


带有 .VSX 扩展名的文件指的是由绘图和形状组成的模板，用于在 Microsoft Visio 中创建图表。VSX 文件以 XML 文件格式保存，并支持至 Visio 2013。
了解更多关于此文件格式的信息 [here](../https://wiki.fileformat.com/image/vsx)。


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


带有 VTX 扩展名的文件是以 XML 文件格式保存到磁盘的 Microsoft Visio 绘图模板。该模板旨在提供一个具有基本设置的文件，可用于创建多个具有相同设置的 Visio 文件。
了解更多关于此文件格式的信息 [here](../https://wiki.fileformat.com/image/vtx)。


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW 是 Visio Graphics Service 文件格式，指定渲染 Web 绘图所需的流和存储。
了解更多关于此文件格式的信息 [here](../https://wiki.fileformat.com/web/vdw)。


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


在 Microsoft Visio 中创建的任何绘图或图表，如果以 XML 格式保存，则具有 .VDX 扩展名。Visio 绘图 XML 文件是在由 Microsoft 开发的 Visio 软件中创建的。
了解更多关于此文件格式的信息 [here](../https://wiki.fileformat.com/image/vdx)。


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


带有 .VSSX 扩展名的文件是使用 Microsoft Visio 2013 及以上版本创建的绘图模板。VSSX 文件格式可在 Visio 2013 及以上版本中打开。Visio 文件以表示各种绘图元素而闻名，例如形状集合、连接器、流程图、网络布局、UML 图等，
了解此文件格式的更多信息，请点击[这里](../https://wiki.fileformat.com/image/vssx)。


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


带有 VSTX 扩展名的文件是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。这些 VSTX 文件提供了创建 Visio 绘图的起始点，保存为 .VSDX 文件，具有默认的布局和设置。
了解此文件格式的更多信息，请点击[这里](../https://wiki.fileformat.com/image/vstx)。


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


带有 VSDM 扩展名的文件是使用支持宏的 Microsoft Visio 应用程序创建的绘图文件。VSDM 文件是类似于 VSDX 的 OPC/XML 绘图，但还提供在打开文件时运行宏的功能。
了解此文件格式的更多信息，请点击[这里](../https://wiki.fileformat.com/image/vsdm)。


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


带有 .VSSM 扩展名的文件是支持宏的 Microsoft Visio 模板文件。打开 VSSM 文件后，可运行宏以实现所需的形状格式化和在图表中的放置。
了解此文件格式的更多信息，请点击[这里](../https://wiki.fileformat.com/image/vssm)。


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


带有 VSTM 扩展名的文件是使用支持宏的 Microsoft Visio 创建的模板文件。与 VSDX 文件不同，基于 VSTM 模板创建的文件可以运行使用 Visual Basic for Applications (VBA) 代码开发的宏。
了解此文件格式的更多信息，请点击[这里](../https://wiki.fileformat.com/image/vstm)。


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
