---
title: "on_conversion_failed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ページ変換が失敗したときに呼び出されるコールバックを登録します。再呼び出し時に以前に設定されたハンドラを置き換えます。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

ページ変換が失敗したときに呼び出されるコールバックを登録します。再呼び出し時に以前に設定されたハンドラを置き換えます。

```python
def on_conversion_failed(self, on_failed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | 失敗を処理する呼び出し可能オブジェクトで、変換されたページコンテキストと失敗の原因となった例外を受け取ります。 |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### 関連項目
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
