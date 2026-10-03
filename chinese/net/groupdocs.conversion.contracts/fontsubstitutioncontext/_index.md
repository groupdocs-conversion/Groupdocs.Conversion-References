---
title: "FontSubstitutionContext"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "描述在加载或渲染源文档时发生的单个字体替换。实例会传递给 OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted。"
type: docs
weight: 250
url: /zh/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

描述在加载或渲染源文档时发生的单个字体替换。实例会传递给 [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted)。

```csharp
public sealed class FontSubstitutionContext
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | 创建一个新的 [`FontSubstitutionContext`](../fontsubstitutioncontext)。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | 源文档引用的字体名称，但在转换管道中不可用。 |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | 替换消息完全按照转换管道报告的原样呈现，未解析。对于结构化暴露字体名称的文档，这可能为 `null`（使用 [`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname)）；对于其他文档，它包含完整的可读描述，列出缺失的字体和替代的字体。 |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | 被转换的源文档的文件名。当源以非 FileStream 的流提供时，此处包含生成的标识符，而不是实际的文件名。 |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | 用作替代的字体名称。对于引擎仅以描述性文本报告替换的文档，可能为 `null`——在这种情况下请读取 [`Reason`](./reason)。 |

### 另见

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
