---
title: "TxtLoadOptions クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "Txt ドキュメントの読み込みオプション。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Txt ドキュメントの読み込みオプション。

プレーンテキストのフォント構成:

TXT ファイルにはフォント情報が含まれていないため、変換中にプレーンテキストコンテンツをレンダリングするフォントを指定するには DefaultTextFont を使用します。

TxtLoadOptions 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | 新しい[`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) インスタンスを初期化します。 |

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
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | 変換中にプレーンテキストコンテンツをレンダリングする際に使用するフォントです。デフォルト: Arial 10pt。 |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | このプロパティは、プレーンテキストドキュメントを変換する際に番号付きリスト項目がどのように認識されるかを指定します。デフォルト値は True です。 |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | Txt ドキュメントを読み込む際に使用されるエンコーディングです。None に設定可能です。デフォルトは None です。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | 入力ドキュメントのファイルタイプです。 |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | 先頭スペースの処理に推奨されるオプションです。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | 余白設定は、[`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/) で定義されています。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | TXT ドキュメントを読み込む際のページサイズオプションです。 |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | 末尾スペースの処理に推奨されるオプションです。デフォルト値は [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/) です。 |

### 関連項目
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
