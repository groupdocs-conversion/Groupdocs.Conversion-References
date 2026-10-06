---
title: "compress メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換結果を圧縮し、Convert に進む継続処理を返します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

変換結果を圧縮し、`Convert` に進む継続を返します。

エントリ段階で圧縮ストリームハンドラを、返されたインターフェイスの廃止されたフルエントチェーンメソッドを使用する代わりに、[`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/)（`OnCompressionCompleted` 設定）を介して登録します。

```python
def compress(self, options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 圧縮変換オプション。 |

**Returns:** Continuation that proceeds to `Convert`.

### 関連項目
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
