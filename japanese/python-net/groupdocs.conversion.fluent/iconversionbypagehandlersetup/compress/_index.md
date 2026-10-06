---
title: "compress メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "指定されたオプションを使用して変換結果を圧縮します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/compress/
is_root: false
weight: 1010
---


## compress {#options}

指定されたオプションを使用して変換結果を圧縮します。

このメソッドを呼び出して変換結果を圧縮します。圧縮ストリームハンドラは、返されたインターフェイスの廃止されたフルエントチェーンメソッドではなく、エントリ段階で [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) を使用して登録します（`OnCompressionCompleted` を設定）。

```python
def compress(self, options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 圧縮変換オプション。 |

**Returns:** Continuation that proceeds to `Convert`.

### 関連項目
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
