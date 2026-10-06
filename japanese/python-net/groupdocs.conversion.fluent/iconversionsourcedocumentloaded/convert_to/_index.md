---
title: "convert_to メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換されたドキュメントをファイルとして保存します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

変換されたドキュメントをファイルとして保存します。

```python
def convert_to(self, file_name):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_name | `str` | 変換されたドキュメント。 |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

変換されたドキュメントをストリームとして保存します。

```python
def convert_to(self, converted_stream_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | 変換されたドキュメントストリームプロバイダー converted_stream_provider arg1arg1: 保存コンテキスト |

**Returns:** Options or handler setup interface to continue conversion building

### 関連項目
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
