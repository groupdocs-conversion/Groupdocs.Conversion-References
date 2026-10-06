---
title: "TsvLoadOptions クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "TSV ドキュメントの読み込みオプションを表します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/tsvloadoptions/
is_root: false
weight: 480
---


## TsvLoadOptions class

TSV ドキュメントの読み込みオプションを表します。

TsvLoadOptions 型は次のメンバーを公開します：

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/__init__/) | 新しい [`TsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/) のインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | 現在のインスタンスをクローンします。（[`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) から継承） |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。(inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | デフォルトのハッシュ関数として機能します。(inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_built_in_document_properties/) | このプロパティはドキュメントから組み込みメタデータプロパティを削除します。 |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_custom_document_properties/) | このプロパティはドキュメントからカスタムメタデータプロパティを削除します。 |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owned/) | ドキュメントコンテナ内の所有ドキュメントを変換するかどうかを制御するオプション。 |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owner/) | ドキュメントのコンテナ自体を変換するかどうかを制御するオプション。true の場合、コンテナが最初に変換されるドキュメントになります。 |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/default_font/) | フォントが見つからない場合に使用するフォント。 |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/depth/) | 変換を実行する深さのレベル数を制御するオプション。 |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/font_substitutes/) | フォント置換。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/format/) | 入力ドキュメントのファイルタイプです。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/margin_settings/) | ページ余白設定。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/size_settings/) | ページサイズ設定。 |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/skip_external_resources/) | このプロパティは外部リソースをロードするかどうかを決定します。True の場合、[`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) リストに含まれるものを除き、すべての外部リソースはロードされません。デフォルト: True。 |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/whitelisted_resources/) | 常にロードされる外部リソース。 |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | このプロパティはシートのすべての列コンテンツが結果の単一ページにレンダリングされるかどうかを決定します。（[`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) から継承） |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | 変換時に行が自動調整されます。（[`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) から継承） |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | このプロパティはセル関連オブジェクトを変更する際に Excel ファイルの制限がチェックされるかどうかを決定します。（[`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) から継承） |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | ワークシートをページに分割する際に使用されるページあたりの列数。デフォルトは 0 で、ページングが無効になります。（[`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) から継承） |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | 非スプレッドシート形式に変換する際の範囲（例: "D1:F8"）。（[`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) から継承） |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | ファイルがロードされる際に使用されるシステムカルチャ情報です。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | このプロパティは、数式計算エラーを無視するかどうかを示します。エラーはサポートされていない関数や外部リンクなどが原因となる場合があります。デフォルトは False です。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | このプロパティは、各シートの内容が PDF ドキュメント内で単一ページに変換されるかどうかを示します。デフォルト値は True です。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | PDF に変換する際に True に設定すると、印刷品質よりもファイルサイズの小ささを優先して変換が最適化されます。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | 保護されたドキュメントの保護を解除するために使用されるパスワードです。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | PDF に変換する際にドキュメント構造を保持するかどうかを示すフラグです（デフォルトは False）。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | シートとともにコメントが印刷される方法です。デフォルトは PrintNoComments です。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | ドキュメントをロードする前にフォントフォルダーがリセットされます。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | ワークシートをページに分割する際に使用されるページあたりの行数です。デフォルトの 0 はページ分割なしを意味します。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | 変換対象のシートインデックスのリストです。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | 変換対象のシート名です。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Excel ファイルを変換する際にグリッド線を表示するオプションです。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Excel ファイルを変換する際に非表示シートを表示するオプションです。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | 変換時に空の行と列をスキップする設定です。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | このプロパティは、スプレッドシートドキュメントを変換する際にフッターをスキップするかどうかを決定します。デフォルトは False です。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | スプレッドシートドキュメントを変換する際にヘッダーをスキップするオプションです。デフォルトは False です。(継承元: [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |

### 関連項目
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
