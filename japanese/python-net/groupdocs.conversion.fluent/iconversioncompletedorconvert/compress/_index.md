---
title: "compress メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換結果を圧縮します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/compress/
is_root: false
weight: 1010
---


## compress {#options}

変換結果を圧縮します。

エントリ段階で圧縮ストリームハンドラを、[`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) を介して（`OnCompressionCompleted` を設定）登録し、返されたインターフェイス上の廃止されたフルエントチェーンメソッドではなく行います。

```python
def compress(self, options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 圧縮変換オプション |

**Returns:** Continuation that proceeds to `Convert`.

### 関連項目
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
