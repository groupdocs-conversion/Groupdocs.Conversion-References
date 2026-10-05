---
title: "set 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "向缓存中插入缓存条目。"
type: docs
url: /zh/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

向缓存中插入缓存条目。

```python
def set(self, key, value):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | `str` | 缓存条目的唯一标识符。 |
| value | `Any` | 要插入的对象。 |

### 示例

```python
from groupdocs.conversion import ConverterSettings, FileCache

# 使用基于文件的缓存创建转换器设置
settings = ConverterSettings()
settings.cache = FileCache()

# 在缓存中存储对象
settings.cache.set("my_document", document)
```

### 另见
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
