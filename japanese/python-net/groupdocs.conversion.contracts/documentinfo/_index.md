---
title: "DocumentInfo クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "多態的なドキュメント情報を取得するための基本実装です。"
type: docs
url: /ja/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

多態的なドキュメント情報を取得するための基本実装です。

インスタンスは `Converter.get_document_info()` によって返され、フォーマット、ページ数、作成日、サイズ、フォーマット固有の属性などのメタデータを公開します。

DocumentInfo 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | ドキュメントの作成日。 |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | ドキュメントのフォーマット。 |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | ドキュメントの総ページ数。 |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | このプロパティは [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/) を実装します。 |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | ドキュメントのサイズ（バイト単位）。 |

### 例

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# 使用例
show_document_info("./lorem-ipsum.txt")
```

### 関連項目
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
