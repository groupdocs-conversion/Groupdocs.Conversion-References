---
title: "FontTransformation クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ドキュメントの読み込みとフォント代替の後に適用される、フォント属性を含むフォント変換設定について説明します。"
type: docs
url: /ja/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

ドキュメントの読み込みとフォント代替の後に適用される、フォント属性を含むフォント変換設定について説明します。

FontTransformation 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | サイズとスタイルが一致する正確なフォントマッチングでフォント変換を作成します（サイズとスタイルは一致する必要があります）。 |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | 名前だけでフォント変換を作成し、任意のサイズとスタイルにマッチさせ、置換フォントが元のフォントのサイズとスタイルを保持します。 |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | 柔軟なマッチングオプションでフォント変換を作成します。 |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。(inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | デフォルトのハッシュ関数として機能します。(inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | このプロパティは、元のフォント名の任意のサイズがマッチするか（true）、`OriginalFont` で指定された正確なフォントサイズのみがマッチするか（false）を示します。 |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | このプロパティは、元のフォントの任意のスタイル（太字、斜体、下線）がマッチするか（True）、`OriginalFont` で指定された正確なフォントスタイルが必要か（False）を決定します。 |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | マッチおよび置換する元のフォント仕様です。 |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | 置換フォントの仕様です。 |

### 関連項目
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
