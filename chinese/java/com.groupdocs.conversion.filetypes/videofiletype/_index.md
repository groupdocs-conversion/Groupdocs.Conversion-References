---
title: "VideoFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义视频文档，包含以下类型。了解视频格式的更多信息。"
type: docs
weight: 26
url: /zh/java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

定义视频文档，包含以下类型： , , , , , , , 了解视频格式的更多信息，请点击[这里](../https://docs.fileformat.com/video/)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [VideoFileType()](#VideoFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Mp4](#Mp4) | MP4（全称 MPEG-4 第 14 部分）是一种基于 ISO/IEC 14496-12:2004 的文件格式，源自 QuickTime 文件格式，但正式规定了对初始对象描述符（IOD）和其他 MPEG 特性的支持。 |
|
|  | [Avi](#Avi) | AVI 文件格式是一种由 Microsoft 引入的音视频多媒体容器文件格式。 |
|
|  | [Flv](#Flv) | FLV（Flash 视频）是一种带有 .flv 扩展名的容器文件格式。 |
|
|  | [Mkv](#Mkv) | MKV（Matroska 视频）是一种类似于 MOV 和 AVI 格式的多媒体容器，但它支持在同一文件中包含多个音频和字幕轨道。 |
|
|  | [Mov](#Mov) | MOV 或 QuickTime 文件格式是由 Apple 开发的多媒体容器：包含一个或多个轨道，每个轨道保存特定类型的数据，例如 |
|
|  | [Webm](#Webm) | 带有 .webm 扩展名的文件是一种基于开放、免版税的 WebM 文件格式的视频文件。 |
|
|  | [Wmv](#Wmv) | Windows Media Video 是由 Microsoft 开发的压缩视频格式。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


序列化构造函数


### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4（全称 MPEG-4 第 14 部分）是一种基于 ISO/IEC 14496-12:2004 的文件格式，源自 QuickTime 文件格式，但正式规定了对初始对象描述符（IOD）和其他 MPEG 特性的支持。了解此文件格式的更多信息，请点击[这里](../https://docs.fileformat.com/video/mp4/)。


### Avi {#Avi}
```
public static final VideoFileType Avi
```


AVI 文件格式是一种由 Microsoft 引入的音视频多媒体容器文件格式。它保存使用多种编解码器（如 XVid 和 DivX）创建并压缩的音频和视频数据。了解此文件格式的更多信息，请点击[这里](../https://docs.fileformat.com/video/avi/)。


### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV（Flash 视频）是一种带有 .flv 扩展名的容器文件格式。FLV 通过 Adobe Flash Player 或 Adobe Air 在互联网上传输音频/视频内容。了解此文件格式的更多信息，请点击[这里](../https://docs.fileformat.com/video/flv/)。


### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV（Matroska 视频）是一种类似于 MOV 和 AVI 格式的多媒体容器，但它支持在同一文件中包含多个音频和字幕轨道。MKV 文件是用于视频的 Matroska 多媒体容器格式。了解此文件格式的更多信息，请点击[这里](../https://docs.fileformat.com/video/mkv/)。


### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV 或 QuickTime 文件格式是由 Apple 开发的多媒体容器：包含一个或多个轨道，每个轨道保存特定类型的数据，例如视频、音频、文本等。了解此文件格式的更多信息，请点击[这里](../https://docs.fileformat.com/video/mov/)。


### Webm {#Webm}
```
public static final VideoFileType Webm
```


带有 .webm 扩展名的文件是一种基于开放、免版税的 WebM 文件格式的视频文件。它专为在网络上共享视频而设计，并定义了包括视频和音频格式在内的文件容器结构。了解此文件格式的更多信息，请点击[这里](../https://docs.fileformat.com/video/webm//)。


### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video 是 Microsoft 开发的压缩视频格式。经过电影与电视工程师学会 (SMPTE) 的标准化后，WMV 现在被视为开放标准格式。了解更多关于此文件格式的信息，请点击[here](../https://docs.fileformat.com/video/wmv/)。


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
