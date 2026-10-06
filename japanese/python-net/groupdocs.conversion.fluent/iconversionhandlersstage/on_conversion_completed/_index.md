---
title: "on_conversion_completed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ドキュメント変換が正常に完了したときに呼び出されるコールバックを登録し、再呼び出し時に以前に設定されたハンドラを置き換えます。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

ドキュメント変換が正常に完了したときに呼び出されるコールバックを登録し、再呼び出し時に以前に設定されたハンドラを置き換えます。

```python
def on_conversion_completed(self, on_completed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | 完了を処理するアクションで、変換コンテキストを受け取ります。 |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained. Returns `IConversionHandlersStage`.

### 関連項目
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
