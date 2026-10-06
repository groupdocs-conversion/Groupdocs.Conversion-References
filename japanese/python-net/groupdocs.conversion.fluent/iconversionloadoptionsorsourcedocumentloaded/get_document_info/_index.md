---
title: "get_document_info メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ページ数やファイルタイプ固有のその他のプロパティを含む、ソースドキュメント情報を取得します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

ページ数やファイルタイプ固有のその他のプロパティを含む、ソースドキュメント情報を取得します。

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details about the source document, such as format, page count, creation date, size, and type‑specific properties.

### 例

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### 関連項目
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
