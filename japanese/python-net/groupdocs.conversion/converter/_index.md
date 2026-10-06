---
title: "Converter クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ドキュメント変換プロセスを制御するメインクラスを表します。"
type: docs
url: /ja/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

ドキュメント変換プロセスを制御するメインクラスを表します。

Converter 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Converter の新しいインスタンスを初期化します。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | 新しい [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) インスタンスを初期化します。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | 新しい [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) インスタンスを初期化します。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | 明示的な変換イベントを使用して新しい Converter を初期化します。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | 明示的な変換イベントを使用して新しい Converter インスタンスを初期化します。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | 新しい Converter インスタンスを初期化します。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | 新しい [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) インスタンスを初期化します。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | 新しい [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) クラスのインスタンスを初期化します。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | 明示的な変換イベントを使用して新しい Converter を初期化します。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | 明示的な変換イベントを使用して新しい Converter を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | ソースドキュメントを変換し、変換されたドキュメント全体を保存します。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | ソースドキュメントを変換し、変換されたドキュメント全体を保存します。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | ソースドキュメントを変換し、変換されたドキュメント全体を保存します。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | ソースドキュメントを変換し、変換されたドキュメント全体を保存します。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | ソースドキュメントを変換し、変換されたドキュメント全体を保存します。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | ソースドキュメントを変換し、変換されたドキュメントをページ単位で保存します。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | ソースドキュメントを変換し、変換されたドキュメントをページ単位で保存します。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | ソースドキュメントを変換し、変換されたドキュメントをページ単位で保存します。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | ソースドキュメントを変換し、変換されたドキュメントをページ単位で保存します。 |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | リソースを解放します。 |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | サポートされているすべての変換を取得します。 |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | ページ数やファイルタイプ固有のその他のプロパティを含む、ソースドキュメント情報を取得します。 |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | ソース文書に対する可能な変換を取得します。 |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | 指定されたドキュメント拡張子に対するサポートされている変換を取得します。 |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | ソースドキュメントがパスワードで保護されているかどうかを確認します。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
`Converter` を使用するタスク ガイド:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### 関連項目
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
