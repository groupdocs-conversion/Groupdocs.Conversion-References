---
title: "DatabaseFileType クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "データベースドキュメントを定義します。"
type: docs
url: /ja/python-net/groupdocs.conversion.filetypes/databasefiletype/
is_root: false
weight: 40
---


## DatabaseFileType class

データベースドキュメントを定義します。以下のファイルタイプが含まれます。

- [`DatabaseFileType.nsf`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/)
- [`DatabaseFileType.log`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/)
- [`DatabaseFileType.sql`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/)

DatabaseFileType 型は以下のメンバーを公開します：

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/__init__/) | シリアル化用に新しい DatabaseFileType を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | 現在のオブジェクトを他と比較します。（[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) によって定義された等価比較を実装します。（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | （[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | 提供されたファイル拡張子の FileType を取得します。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | 指定された file_name の FileType を返します。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | 提供されたドキュメントストリームの FileType を返します。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | （[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | デフォルトのハッシュ関数を提供します。（[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | ファイルタイプの文字列表現です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | ファイルタイプの説明です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | ファイル拡張子です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | ファイルファミリーです。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | ファイル形式です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [NSF](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/) | .nsf（Notes Storage Facility）拡張子のファイルは、IBM Notes ソフトウェア（旧 Lotus Notes）で使用されるデータベースファイル形式です。メール、予定、ドキュメント、フォーム、ビューなど、さまざまなオブジェクトを格納するスキーマを定義します。このファイル形式の詳細はここをご覧ください。 |
| [LOG](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/) | .log 拡張子のファイルは、タイムスタンプ付きのプレーンテキストのリストを含みます。通常、ソフトウェアや OS が特定のアクティビティの詳細を記録し、開発者やユーザーが特定の期間に何が起こったかを追跡できるようにします。このファイル形式の詳細はここをご覧ください。 |
| [SQL](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/) | .sql 拡張子のファイルは、構造化照会言語（SQL）ファイルで、リレーショナルデータベースで動作するコードを含みます。データベースに対する CRUD（作成、読み取り、更新、削除）操作のための SQL 文を書くために使用されます。このファイル形式の詳細はここをご覧ください。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 不明なファイルタイプ（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |

### 関連項目
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
