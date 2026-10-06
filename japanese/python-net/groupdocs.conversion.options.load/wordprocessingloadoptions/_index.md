---
title: "WordProcessingLoadOptions クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "WordProcessing ドキュメントの読み込みオプションを提供します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

WordProcessing ドキュメントの読み込みオプションを提供します。

フォント処理パイプライン：

フェーズ 1 - フォント置換（ドキュメント読み込み中）:
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

フェーズ 2 - フォント置換（ドキュメント読み込み後）:
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

WordProcessingLoadOptions 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | 新しいインスタンスの [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。(inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | デフォルトのハッシュ関数として機能します。(inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | auto_detect_rtl_direction プロパティは、主に右から左のテキストを含む段落やランの bidi フラグが変換前に修正されるかどうかを決定します。 |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | ブックマークオプション。 |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | Word 処理ドキュメントを読み込む際に組み込みドキュメントプロパティがクリアされるかどうかを示すフラグです。 |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | ClearCustomDocumentProperties プロパティです。 |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | コメント表示モードは、出力ドキュメントでコメントをどのように表示するかを指定します。デフォルトは `ShowInBalloons` です。 |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | このプロパティは [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) を実装します。デフォルトは False です。 |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | convert_owner フラグは、ドキュメントの所有者を変換するかどうかを示します。デフォルトは True です。 |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | WordProcessing ドキュメントのデフォルトフォントです。 |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | ドキュメントコンテナロードオプションの深さです。デフォルトは 1 です。 |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | embed_true_type_fonts プロパティは、TrueType フォントが出力ドキュメントに埋め込まれるかどうかを決定します。デフォルトは True です。 |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | このプロパティは、システムの FontConfig に基づく欠損フォントの自動置換を有効にします。デフォルトは False です。 |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | このフラグは、ドキュメント内の FontInfo に基づく欠損フォントの自動置換を有効にします。デフォルト: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | このプロパティは、フォント名に基づいて欠損フォントが自動的に置換されるかどうかを示します。デフォルト: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | WordProcessing ドキュメントを変換する際に使用されるフォント代替です。 |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | ドキュメントの読み込みとフォント置換が完了した後に適用されるフォント変換で、正常に読み込まれたフォントを含むドキュメント内の任意のフォントを変更できます。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | 入力ドキュメントのファイルタイプです。 |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | hide_word_tracked_changes プロパティは、Word ドキュメントのマークアップと変更履歴を非表示にします。 |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | WordProcessing ドキュメントのハイフネーションオプションです。 |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | keep_date_field_original_value プロパティは、日付フィールドの元の値を保持するかどうかを決定します。デフォルトは False です。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | 余白設定です。 |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | 変換されたドキュメントのページ番号生成フラグです（デフォルト: False）。 |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | 保護されたドキュメントの保護を解除するためのパスワードです。 |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | PDFに変換する際にドキュメント構造を保持すべきかを示すフラグ（デフォルトは False）。 |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | Microsoft Word のフォームフィールドが生成された PDF でフォームフィールドとして保持されるかテキストに変換されるかを示すプロパティ。デフォルトは False。 |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | True に設定すると、コメントにフルコメント投稿者名が表示されます。デフォルトは False。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | WordProcessing ドキュメントのサイズ設定（[`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)）。 |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | ドキュメントを読み込む際に外部リソースをスキップするかどうかを決定するフラグ。 |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | 読み込み後にフィールドを更新するオプション。デフォルト: False。 |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | 読み込み後にページレイアウトが更新されます。デフォルト: False。 |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | カーニング表示を改善するためにテキストシェイパーを使用するかどうかを示すプロパティ。デフォルトは False。 |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | 外部コンテンツの読み込みに使用するホワイトリスト化されたリソース（[`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) を実装）。 |

### 例

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
`WordProcessingLoadOptions` を使用するタスクガイド：

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### 関連項目
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
