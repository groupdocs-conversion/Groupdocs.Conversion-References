---
title: "convert_by_page_to 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "将已转换的页面保存为流。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

将已转换的页面保存为流。

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | 已转换文档页面流提供程序。 |

**Returns:** Page options or handler setup interface to continue conversion building.

### 另见
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
