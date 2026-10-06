---
title: "compress メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換結果を圧縮します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionhandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

変換結果を圧縮します。

エントリ段階で圧縮ストリームハンドラを、返されたインターフェイスの廃止されたフルエントチェーンメソッドではなく、[`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/)（`OnCompressionCompleted` 設定）を介して登録します。

```python
def compress(self, options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 圧縮変換オプション |

**Returns:** Continuation that proceeds to `Convert`.

### 関連項目
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
