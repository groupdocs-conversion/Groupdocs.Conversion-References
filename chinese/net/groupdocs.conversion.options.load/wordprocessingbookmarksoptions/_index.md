---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "处理 WordProcessing 中书签的选项"
type: docs
weight: 2930
url: /zh/net/groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
## WordProcessingBookmarksOptions class

处理 WordProcessing 中书签的选项

```csharp
public class WordProcessingBookmarksOptions : ValueObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WordProcessingBookmarksOptions](wordprocessingbookmarksoptions)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BookmarksOutlineLevel](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/bookmarksoutlinelevel) { get; set; } | 指定在文档大纲中显示 Word 书签的默认级别。默认值为 0。有效范围为 0 到 9。 |
| [ExpandedOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/expandedoutlinelevels) { get; set; } | 指定在查看文件时文档大纲中展开显示的层级数。默认值为 0。有效范围为 0 到 9。请注意，此选项在保存为 XPS 时无效。 |
| [HeadingsOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/headingsoutlinelevels) { get; set; } | 指定在文档大纲中包含多少级标题（使用 Heading 样式格式化的段落）。默认值为 0。有效范围为 0 到 9。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
