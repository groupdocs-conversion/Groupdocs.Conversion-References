---
title: "VideoConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为视频类型的选项。"
type: docs
weight: 2280
url: /zh/net/groupdocs.conversion.options.convert/videoconvertoptions/
---
## VideoConvertOptions class

转换为视频类型的选项。

```csharp
public sealed class VideoConvertOptions : ConvertOptions<VideoFileType>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VideoConvertOptions](videoconvertoptions)() | 初始化 [`VideoConvertOptions`](../videoconvertoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AudioFormat](../../groupdocs.conversion.options.convert/videoconvertoptions/audioformat) { get; set; } | 要使用的音频格式是什么 |
| [ExtractAudioOnly](../../groupdocs.conversion.options.convert/videoconvertoptions/extractaudioonly) { get; set; } | 如果设置为 true，则从视频中提取音频 |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 输入文档应转换成的目标文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 实现 [`Format`](../iconvertoptions/format) |
| [FramesPerSecond](../../groupdocs.conversion.options.convert/videoconvertoptions/framespersecond) { get; set; } | 每秒帧数。默认值为 30。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 克隆当前选项实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [VideoFileType](../../groupdocs.conversion.filetypes/videofiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
