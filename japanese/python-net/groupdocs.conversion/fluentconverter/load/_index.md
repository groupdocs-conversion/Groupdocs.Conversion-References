---
title: "load メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換用のソースドキュメントを構成します。"
type: docs
url: /ja/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

変換用のソースドキュメントを構成します。

```python
def load(cls, file_name):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_name | `str` | ソースドキュメント。 |

## load {#file_name}

ソースドキュメントのセットを構成します。

```python
def load(cls, file_name):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_name | `list[str]` | ソースファイルの配列。 |

## load {#document_stream_provider}

ソースドキュメントストリームを構成します。

```python
def load(cls, document_stream_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | ソースドキュメントストリームプロバイダー。 |

## load {#document_stream_provider}

ソースドキュメントストリームのセットを構成します。

```python
def load(cls, document_stream_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | ソース文書ストリームプロバイダーのセット。 |

### 関連項目
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
