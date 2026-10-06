---
title: "with_events メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "エントリ段階で変換ライフサイクルイベントハンドラを使用してフルエントチェーンを開始します。"
type: docs
url: /ja/python-net/groupdocs.conversion/fluentconverter/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

エントリ段階で変換ライフサイクルイベントハンドラを使用してフルエントチェーンを開始します。

```python
def with_events(cls, configure):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | `ConversionEvents` のバッグを変更する Callable。 |

**Returns:** The source-selection stage, allowing `Load` to be chained.

### 関連項目
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
