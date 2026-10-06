---
title: "with_events メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "コンバータのライフタイム中に存在し、すべての変換実行時に発火する ConversionEvents バッグ上に変換ライフサイクルイベントハンドラを登録します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

変換のライフサイクルイベントハンドラを、コンバータの存続期間中に存在し、各変換実行時に発火する [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) バッグに登録します。

同じエントリ段階に位置します [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/)。複数回の呼び出しは蓄積されます：同じ内部バッグが各 `configure` アクションに渡されるため、以前の呼び出しで設定されたハンドラは、後の呼び出しで上書きされない限り残ります。

```python
def with_events(self, configure):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | イベントバッグを変更するアクション。 |

**Returns:** The source-selection stage so that `Load` may be chained.

### 関連項目
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
