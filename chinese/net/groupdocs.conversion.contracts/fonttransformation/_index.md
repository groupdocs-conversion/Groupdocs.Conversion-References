---
title: "FontTransformation"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "描述包括字体属性的字体转换配置。字体转换在文档加载和字体替换后应用。"
type: docs
weight: 260
url: /zh/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

描述包括字体属性的字体转换配置。字体转换在文档加载和字体替换后应用。

```csharp
public class FontTransformation : ValueObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | 为 true 时，匹配原始字体名称的任何字号；为 false 时，匹配 OriginalFont 中指定的精确字号。 |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | 为 true 时，匹配原始字体的任何样式（粗体、斜体、下划线）；为 false 时，匹配 OriginalFont 中指定的精确样式。 |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | 用于匹配和替换的原始字体规范。 |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | 替换字体规范。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | 创建一个具有精确字体匹配（字号和样式必须匹配）的字体转换。 |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | 仅通过名称创建字体转换，匹配任何字号和样式。替换字体将保留原始字体的字号和样式。 |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | 创建一个具有灵活匹配选项的字体转换。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
