---
title: "with_events メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "コンバータのライフタイム中に存続し、各変換実行時に発火する ConversionEvents バッグ上に変換ライフサイクルイベントハンドラを登録します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

コンバータのライフタイム中に存続し、各変換実行時に発生する [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) バッグ上に変換ライフサイクルイベントハンドラを登録します。

[`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/) の前後で呼び出すことができます。
複数回呼び出すと蓄積されます。同じ内部バッグが各 `configure` アクションに渡されるため、後の呼び出しで上書きされない限り、以前の呼び出しで設定されたハンドラは残ります。

```python
def with_events(self, configure):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | イベントバッグを変更するアクション。 |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### 関連項目
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
