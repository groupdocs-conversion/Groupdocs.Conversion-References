---
title: "compress 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "压缩转换结果。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/compress/
is_root: false
weight: 1010
---


## compress {#options}

压缩转换结果。

在入口阶段通过 [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) 注册压缩流处理程序（设置 `OnCompressionCompleted`），而不是在返回的接口上使用已废弃的流畅链式方法。

```python
def compress(self, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 压缩转换选项。 |

**Returns:** Continuation that proceeds to `Convert`.

### 另见
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
