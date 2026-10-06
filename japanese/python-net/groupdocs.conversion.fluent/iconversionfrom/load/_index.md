---
title: "load メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ソースドキュメントのファイル名を設定します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

ソースドキュメントのファイル名を設定します。

```python
def load(self, file_name):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_name | `str` | ソースドキュメント。 |

## load {#file_name}

ソースドキュメント配列を設定します。

```python
def load(self, file_name):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_name | `list[str]` | ソースドキュメントのセット。 |

## load {#document_stream_provider}

ソースドキュメントストリームを設定します。

```python
def load(self, document_stream_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | ソースドキュメントストリームプロバイダー。 |

| 例外を発生させます | 説明 |
| :- | :- |
| `InvalidConverterSettingsException` | コンバータ設定の検証に失敗した場合。 |

## load {#document_stream_provider}

ソースドキュメントストリームプロバイダーを設定します。

```python
def load(self, document_stream_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | ソースドキュメントストリームプロバイダー。 |

| 例外を発生させます | 説明 |
| :- | :- |
| `InvalidConverterSettingsException` | コンバータ設定の検証に失敗した場合。 |

### 関連項目
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
