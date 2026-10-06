---
title: "on_conversion_completed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ドキュメント変換が正常に完了したときに呼び出されるコールバックを登録します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

ドキュメント変換が正常に完了したときに呼び出されるコールバックを登録します。

```python
def on_conversion_completed(self, on_completed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | 完了を処理するアクションで、変換コンテキストを受け取ります。 |

**Returns:** The flat handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### 関連項目
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
