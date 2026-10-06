---
title: "on_conversion_completed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換されたドキュメントストリームを受け取ります。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

変換された文書ストリームを受け取ります。`ConvertTo(string fileName)` または `ConvertTo(convertedStreamProvider)` が設定されている場合にのみ発火します。

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | 変換されたドキュメントストリームプロバイダー（`ConvertedContext`）。 |

**Returns:** Interface to continue conversion building.

### 関連項目
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
