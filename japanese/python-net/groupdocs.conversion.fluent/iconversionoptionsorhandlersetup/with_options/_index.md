---
title: "with_options メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換プロセスの変換オプションを設定します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

変換プロセスの変換オプションを設定します。

```python
def with_options(self, convert_options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 変換オプション。 |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

プロバイダー関数を使用して変換オプションを設定します。

```python
def with_options(self, options_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | 変換コンテキストに基づいて変換オプションを提供する関数。 |

**Returns:** Handler setup interface to continue conversion building.

### 関連項目
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
