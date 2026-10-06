---
title: "with_options メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ロードオプションを設定します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

ロードオプションを設定します。

```python
def with_options(self, load_options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| load_options | `LoadOptions` | ロードオプション。 |

## with_options {#load_options_provider}

現在読み込まれているドキュメントのロードオプションを提供します。

```python
def with_options(self, load_options_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | ロードオプションプロバイダー。プロバイダーはロードオプションコンテキストを受け取ります。 |

### 関連項目
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
