---
title: "try_get_value メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "指定されたキーに関連付けられたエントリが存在する場合、取得します。"
type: docs
url: /ja/python-net/groupdocs.conversion.caching/icache/try_get_value/
is_root: false
weight: 1070
---


## try_get_value {#key-value}

指定されたキーに関連付けられたエントリが存在する場合、取得します。

```python
def try_get_value(self, key, value):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | `str` | 要求されたエントリを識別するキーです。 |
| value | `Any` | 見つかった値、または None です。 |

**Returns:** bool: True if the key was found.

### 関連項目
* class [`ICache`](/conversion/python-net/groupdocs.conversion.caching/icache/)
