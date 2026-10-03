---
title: "DetectNumberingWithWhitespaces"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "允许指定在转换纯文本文档时如何识别编号列表项。默认值为 true。"
type: docs
weight: 30
url: /zh/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

允许指定在转换纯文本文档时如何识别编号列表项。默认值为 true。

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### 备注

如果此选项设置为 false，列表识别算法将在列表编号以点、右括号或项目符号（如 \"•\", \"*\", \"-\" 或 \"o\"）结尾时检测列表段落。

如果此选项设置为 true，空格也将用作列表编号的分隔符：阿拉伯式编号（1., 1.1.2.）的列表识别算法同时使用空格和点（\".\"）符号。

### 另见

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
