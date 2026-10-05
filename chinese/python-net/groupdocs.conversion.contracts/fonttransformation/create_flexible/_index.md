---
title: "create_flexible 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "创建一个具有灵活匹配选项的字体转换。"
type: docs
url: /zh/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/
is_root: false
weight: 1030
---


## create_flexible {#original_font-replacement_font-match_any_size-match_any_style}

创建一个具有灵活匹配选项的字体转换。

```python
def create_flexible(cls, original_font, replacement_font, match_any_size, match_any_style):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| original_font | `Font` | 用于匹配的字体规范。 |
| replacement_font | `Font` | 用于转换为的字体规范。 |
| match_any_size | `bool` | True 表示匹配任意大小，False 表示匹配精确大小。 |
| match_any_style | `bool` | True 表示匹配任意样式，False 表示匹配精确样式。 |

### 另见
* class [`FontTransformation`](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/)
