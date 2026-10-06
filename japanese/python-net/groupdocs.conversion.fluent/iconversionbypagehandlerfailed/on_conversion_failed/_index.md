---
title: "on_conversion_failed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ページ変換が失敗したときに呼び出されるコールバックを登録します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

ページ変換が失敗したときに呼び出されるコールバックを登録します。

```python
def on_conversion_failed(self, on_failed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | 失敗を処理するアクションで、変換されたページコンテキストと失敗の原因となった例外を受け取ります。 |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### 関連項目
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
