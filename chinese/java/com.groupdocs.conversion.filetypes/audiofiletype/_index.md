---
title: "AudioFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义音频文档，包含以下类型          了解更多关于音频格式的信息 此处。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

定义音频文档，包含以下类型： , , , , , , , , , 了解更多关于音频格式的信息 [此处](../https://docs.fileformat.com/audio/)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [AudioFileType()](#AudioFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Mp3](#Mp3) | 扩展名为 .mp3 的文件是基于 MPEG-1 音频层 III 或 MPEG-2 音频层 III 的数字编码音频文件格式。 |
|
|  | [Aac](#Aac) | AAC（Advanced Audio Coding）指的是基于有损音频压缩的数字音频编码标准，用于表示音频文件。 |
|
|  | [Aiff](#Aiff) | 该 AIFF（Audio Interchange File Format）是一种由 Apple 于 1998 年开发的无压缩音频文件格式，但基于 EA IFF 85。了解更多关于此文件格式的信息 [此处](../https://docs.fileformat.com/audio/aiff/)。 |
|
|  | [Flac](#Flac) | FLAC（Free Lossless Audio Codec）是一种由 Xiph.Org Foundation 开发的无损压缩音频编码格式。了解更多关于此文件格式的信息 [此处](../https://docs.fileformat.com/audio/flac/)。 |
|
|  | [M4a](#M4a) | 该 M4A 文件格式是一种使用 AAC（Advanced Audio Coding）创建的音频文件，属于有损压缩。 |
|
|  | [Wma](#Wma) | 扩展名为 .wma 的文件表示以高级系统格式（ASF）保存的音频文件。 |
|
|  | [Ac3](#Ac3) | 带有 .ac3 扩展名的文件是由 Dolby Laboratories 推出的 Audio Codec 3 文件。 |
|
|  | [Ogg](#Ogg) | OGG 是一种 Ogg Vorbis 压缩音频文件，保存为 .ogg 扩展名。 |
|
|  | [Wav](#Wav) | WAV，因 WAVE（波形音频文件格式）而闻名，是 Microsoft 的资源互换文件格式（RIFF）规范的一个子集，用于存储数字音频文件。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


序列化构造函数


### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


带有 .mp3 扩展名的文件是基于 MPEG-1 Audio Layer III 或 MPEG-2 Audio Layer III 的数字音频文件格式。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/audio/mp3/)。


### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC（Advanced Audio Coding）指的是基于有损音频压缩的数字音频编码标准。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/audio/aac/)。


### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


该 AIFF（Audio Interchange File Format）是一种由 Apple 于 1998 年开发的无压缩音频文件格式，但基于 EA IFF 85。了解更多关于此文件格式的信息 [此处](../https://docs.fileformat.com/audio/aiff/)。


### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC（Free Lossless Audio Codec）是一种由 Xiph.Org Foundation 开发的无损压缩音频编码格式。了解更多关于此文件格式的信息 [此处](../https://docs.fileformat.com/audio/flac/)。


### M4a {#M4a}
```
public static final AudioFileType M4a
```


M4A 文件格式是一种使用 AAC（Advanced Audio Coding）创建的音频文件，属于有损压缩。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/audio/m4a/)。


### Wma {#Wma}
```
public static final AudioFileType Wma
```


带有 .wma 扩展名的文件表示以 Advanced Systems Format（ASF）格式保存的音频文件。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/audio/wma/)。


### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


带有 .ac3 扩展名的文件是由 Dolby Laboratories 推出的 Audio Codec 3 文件。这是一种可容纳多达六个声道的音频格式。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/audio/ac3/)。


### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG 是一种 Ogg Vorbis 压缩音频文件，保存为 .ogg 扩展名。OGG 文件用于存储音频数据，并且可以包含艺术家、曲目信息以及元数据。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/audio/ogg/)。


### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV，因 WAVE（波形音频文件格式）而闻名，是 Microsoft 的资源互换文件格式（RIFF）规范的一个子集，用于存储数字音频文件。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/audio/ogg/)。


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
