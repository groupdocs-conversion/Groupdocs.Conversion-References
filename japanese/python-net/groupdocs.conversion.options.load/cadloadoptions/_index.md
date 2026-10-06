---
title: "CadLoadOptions クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "CAD ドキュメントの読み込みオプションを提供します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/cadloadoptions/
is_root: false
weight: 60
---


## CadLoadOptions class

CAD ドキュメントの読み込みオプションを提供します。

CadLoadOptions 型は以下のメンバーを公開します：

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/__init__/) | [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/) クラスの新しいインスタンスを初期化します。 |

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
| [background_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/background_color/) | 背景色。 |
| [ctb_sources](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/ctb_sources/) | CTB ソース。 |
| [draw_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_color/) | 前景色。 |
| [draw_type](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_type/) | 描画の種類。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/format/) | 入力ドキュメントのファイルタイプです。 |
| [layout_names](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) | 変換対象のレイアウト名。 |
| [layout_scope](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) | 変換される描画スペースを決定するレイアウトスコープ。デフォルトは[`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)で、変換を制限しません。[`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) が指定されている場合は無視されます。これは、明示的なレイアウト名が常に優先されるためです。`None` 値は[`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/) とみなされます。 |

### 関連項目
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
