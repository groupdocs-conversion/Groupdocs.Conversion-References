---
title: "with_options メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換オプションを設定します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
---


## with_options {#convert_options}

変換オプションを設定します。

```python
def with_options(self, convert_options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 変換オプション |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

変換オプションを設定します。

```python
def with_options(self, convert_options_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | 変換オプション。`ConvertContext` がプロバイダーに渡されます。 |

**Returns:** Interface to continue conversion building.

### 関連項目
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
