---
title: "on_conversion_completed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換されたページストリームを受け取ります。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

変換されたページストリームを受け取ります。`ConvertTo(convertedStreamProvider)` が設定されている場合にのみ発生します。

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | 変換されたページストリームプロバイダー。`ConvertedPageContext`。 |

**Returns:** Interface to continue conversion building.

### 関連項目
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
