---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义用于存储记录集合的演示文件格式，以容纳演示数据，如幻灯片、形状、文本、动画、视频、音频和嵌入对象。"
type: docs
weight: 22
url: /zh/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

定义演示文件格式，用于存储记录集合，以容纳演示数据，例如幻灯片、形状、文本、动画、视频、音频和嵌入对象。
包括以下文件类型：
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
了解更多关于演示格式的信息 [here](../https://wiki.fileformat.com/presentation)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Ppt](#Ppt) | 带有 PPT 扩展名的文件表示 PowerPoint 文件，包含用于以幻灯片放映方式显示的幻灯片集合。 |
|
|  | [Pps](#Pps) | PPS，PowerPoint 幻灯片放映，文件是使用 Microsoft PowerPoint 为幻灯片放映目的创建的。 |
|
|  | [Pptx](#Pptx) | 带有 PPTX 扩展名的文件是使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。 |
|
|  | [Ppsx](#Ppsx) | PPSX，Power Point 幻灯片放映，文件是使用 Microsoft PowerPoint 2007 及以上版本为幻灯片放映目的创建的。 |
|
|  | [Odp](#Odp) | 带有 ODP 扩展名的文件表示在 OASIS Open 标准中由 OpenOffice.org 使用的演示文件格式。 |
|
|  | [Otp](#Otp) | 带有 .OTP 扩展名的文件表示在 OASIS OpenDocument 标准格式中由应用程序创建的演示模板文件。 |
|
|  | [Potx](#Potx) | 带有 .POTX 扩展名的文件表示由 Microsoft PowerPoint 2007 及以上版本创建的 Microsoft PowerPoint 模板演示文稿。 |
|
|  | [Pot](#Pot) | 带有 .POT 扩展名的文件表示由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。 |
|
|  | [Potm](#Potm) | 带有 POTM 扩展名的文件是支持宏的 Microsoft PowerPoint 模板文件。 |
|
|  | [Pptm](#Pptm) | 带有 PPTM 扩展名的文件是启用宏的演示文件，由 Microsoft PowerPoint 2007 或更高版本创建。 |
|
|  | [Ppsm](#Ppsm) | 带有 PPSM 扩展名的文件表示由 Microsoft PowerPoint 2007 或更高版本创建的启用宏的幻灯片放映文件格式。 |
|
|  | [Fodp](#Fodp) | 带有 FODP 扩展名的文件表示 OpenDocument 平面 XML 演示文稿。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


序列化构造函数


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


带有 PPT 扩展名的文件表示 PowerPoint 文件，它由一系列幻灯片组成，用于作为幻灯片放映显示。它指定了 Microsoft PowerPoint 97-2003 使用的二进制文件格式。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/ppt)。


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS，PowerPoint 幻灯片放映，文件是使用 Microsoft PowerPoint 为幻灯片放映目的创建的。PPS 文件的读取和创建受 Microsoft PowerPoint 97-2003 支持。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/pps)。


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


带有 PPTX 扩展名的文件是使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。不同于之前的二进制 PPT 演示文件格式，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文件格式。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/pptx)。


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX，Power Point 幻灯片放映，文件是使用 Microsoft PowerPoint 2007 及以上版本为幻灯片放映目的创建的。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/ppsx)。


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


带有 ODP 扩展名的文件表示在 OASIS Open 标准中由 OpenOffice.org 使用的演示文件格式。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/odp)。


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


带有 .OTP 扩展名的文件表示在 OASIS OpenDocument 标准格式中由应用程序创建的演示模板文件。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/otp)。


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


带有 .POTX 扩展名的文件表示由 Microsoft PowerPoint 2007 及以上版本创建的 Microsoft PowerPoint 模板演示文稿。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/potx)。


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


带有 .POT 扩展名的文件表示由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/pot)。


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


带有 POTM 扩展名的文件是支持宏的 Microsoft PowerPoint 模板文件。POTM 文件由 PowerPoint 2007 或以上版本创建，并包含可用于创建进一步演示文件的默认设置。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/potm)。


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


带有 PPTM 扩展名的文件是启用宏的演示文件，由 Microsoft PowerPoint 2007 或更高版本创建。
了解更多关于此文件格式的信息，请点击[here](../https://wiki.fileformat.com/presentation/pptm)。


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


带有 PPSM 扩展名的文件表示由 Microsoft PowerPoint 2007 或更高版本创建的启用宏的幻灯片放映文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/presentation/ppsm)。


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


扩展名为 FODP 的文件表示 OpenDocument 扁平 XML 演示文稿。演示文稿文件以 OpenDocument 格式保存，但使用扁平 XML 格式，而不是标准 .ODP 文件使用的 .ZIP 容器。


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
