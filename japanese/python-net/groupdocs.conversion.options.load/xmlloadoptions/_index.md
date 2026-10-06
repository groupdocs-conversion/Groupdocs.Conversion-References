---
title: "XmlLoadOptions クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "XML ドキュメントの読み込みオプション。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/xmlloadoptions/
is_root: false
weight: 590
---


## XmlLoadOptions class

XML ドキュメントの読み込みオプション。

XmlLoadOptions 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/__init__/) | 新しい [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/) のインスタンスを初期化します。 |

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
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/custom_css_style/) | 変換中にドキュメントに適用されるカスタム CSS スタイルです。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/format/) | 入力ドキュメントのファイルタイプです。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/margin_settings/) | ページ余白設定。 |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/orientation_settings/) | ページの向き設定です。 |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_layout_options/) | ドキュメントを読み込む際に適用するページレイアウトのスケーリングです。デフォルト: None。 |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_numbering/) | 変換されたドキュメントのページ番号生成フラグです（デフォルト: False）。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/size_settings/) | ページサイズ設定。 |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/) | このプロパティは外部リソースがロードされるかどうかを示します。 |
| [use_as_data_source](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/use_as_data_source/) | XML ドキュメントはデータ ソースとして使用されます。 |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/whitelisted_resources/) | 常にロードされる外部リソース。 |
| [xsl_fo_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xsl_fo_factory/) | XSL-FO マークアップ ファイルを使用して XML を変換するための XSL-FO ドキュメント ストリームです。 |
| [xslt_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xslt_factory/) | XML を XSL 変換して HTML に変換するための XSLT ドキュメント ストリームです。 |
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | HTML のベース パス/URL です。（[`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/) から継承） |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | 最初のパラメータが Uri であるリクエスト ヘッダーを構成するために使用されるアクションです。（[`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/) から継承） |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Uri の認証情報プロバイダーです。（[`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/) から継承） |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | Web ドキュメントを読み込む際に使用されるエンコーディングです。None に設定された場合、エンコーディングはドキュメントの文字セット属性から決定されます。（[`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/) から継承） |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | HTML のレンダリング モードは HTML コンテンツの描画方法を制御します。デフォルト: AbsolutePositioning。（[`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/) から継承） |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | 外部リソースの読み込みタイムアウトです。（[`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/) から継承） |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | このプロパティは変換に PDF を使用するかどうかを示します（デフォルト: False）。（[`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/) から継承） |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | 変換前にドキュメントの `<body>` タグに適用されるズームレベル（パーセンテージ）で、ドキュメントの視覚的外観を拡大縮小します。（[`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/) から継承） |

### 関連項目
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
