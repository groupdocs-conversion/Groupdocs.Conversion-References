---
title: "on_conversion_completed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ページ変換が正常に完了したときに呼び出されるコールバックを登録します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

ページ変換が正常に完了したときに呼び出されるコールバックを登録します。

```python
def on_conversion_completed(self, on_completed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | 完了を処理するアクションで、変換されたページコンテキストを受け取ります。 |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### 関連項目
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
