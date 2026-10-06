---
title: "compress メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換結果を圧縮します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/compress/
is_root: false
weight: 1010
---


## compress {#options}

変換結果を圧縮します。

エントリ段階で圧縮ストリームハンドラを、[`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) を使用して登録します（`OnCompressionCompleted` を設定）。返されたインターフェイスの廃止されたフルエントチェーンメソッドを使用する代わりに。

```python
def compress(self, options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 圧縮変換オプション。 |

**Returns:** Continuation that proceeds to `Convert`.

### 関連項目
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
