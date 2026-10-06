---
title: "compress メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換結果を圧縮します。エントリ段階で IConversionSettings.withevents を使用して圧縮ストリームハンドラを登録し（OnCompressionCompleted を設定）、廃止されたフルエントメソッドの使用を避けます…"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

変換結果を圧縮します；エントリーステージで [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) を介して圧縮ストリームハンドラを登録します（`OnCompressionCompleted` を設定）。廃止された流暢なチェーンメソッドの使用は避けてください。

```python
def compress(self, options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 圧縮変換オプション。 |

**Returns:** Continuation that proceeds to `Convert`.

### 関連項目
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
