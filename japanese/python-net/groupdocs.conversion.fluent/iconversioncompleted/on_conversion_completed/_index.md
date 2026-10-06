---
title: "on_conversion_completed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換されたドキュメントストリームを受け取り、ConvertTo(string fileName) または ConvertTo(convertedStreamProvider) が設定されている場合にのみ発火します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

変換されたドキュメントストリームを受け取り、`ConvertTo(string fileName)` または `ConvertTo(convertedStreamProvider)` が設定されている場合にのみ発生します。

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | 変換されたドキュメントストリームプロバイダー。 |

**Returns:** Interface to continue conversion building.

### 関連項目
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
