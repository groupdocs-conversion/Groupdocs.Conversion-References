---
title: "on_conversion_failed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ドキュメント変換が失敗したときに呼び出されるコールバックを登録します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

ドキュメント変換が失敗したときに呼び出されるコールバックを登録します。再度呼び出すと、以前に設定されたハンドラが置き換えられます。

```python
def on_conversion_failed(self, on_failed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – 失敗を処理するアクションで、変換コンテキストと失敗の原因となった例外を受け取ります。 |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### 関連項目
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
