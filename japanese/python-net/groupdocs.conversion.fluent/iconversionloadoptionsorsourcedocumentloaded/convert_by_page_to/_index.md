---
title: "convert_by_page_to メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換されたページをストリームとして保存します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

変換されたページをストリームとして保存します。

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | 変換されたドキュメントページストリームプロバイダー。 |

**Returns:** Page options or handler setup interface to continue conversion building.

### 関連項目
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
