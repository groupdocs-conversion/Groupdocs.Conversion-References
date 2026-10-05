---
title: "reason 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "替换消息完全按照转换管道报告的原样呈现，未解析。"
type: docs
url: /zh/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/
is_root: false
weight: 2020
---


## reason property

替换消息完全按照转换管道报告的原样呈现，未解析。

对于结构化公开字体名称的文档，这可能为 None（使用 [`FontSubstitutionContext.original_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) / [`FontSubstitutionContext.substitute_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/)）；对于其他文档，它包含完整的可读描述，其中同时列出缺失的字体和替代的字体。

### Definition:
```python
@property
def reason(self):
    ...
```

### 另见
* class [`FontSubstitutionContext`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/)
