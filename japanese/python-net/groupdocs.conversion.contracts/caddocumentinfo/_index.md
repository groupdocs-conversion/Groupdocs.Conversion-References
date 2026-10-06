---
title: "CadDocumentInfo クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "Cad ドキュメントのメタデータを含みます。"
type: docs
url: /ja/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Cad ドキュメントのメタデータを含みます。

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

明示的な[`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) がない場合、これらのシートはモデル空間となり、常にプロット可能であるため常にシートとなります。また、保存されたページ設定に正の幅と高さがあるすべてのペーパー空間レイアウトも含まれ、[`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) によって絞り込まれます。明示的なレイアウト名が指定されると、シートは描画が保持する提供された名前に順序通りに一致し、スコープやページ設定による除外は行われません。

DWF の場合、公開されたページセットが報告されます。1 未満のカウントは 0 で、要求されたスコープが対象となるシートと一致しないときに報告されます：メタデータは依然として描画を記述し、0 はスコープが何も選択しないことを示し、描画が保持するものを尋ねた呼び出し元が失敗するわけではありません。同じロードオプションでの変換は失敗します。

したがって、このカウントは [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) のサイズではありません。このプロパティは、シートとして公開できないものも含め、描画が保持するすべてのプロット構成を一覧表示し、特定の変換が何ページ出力するかを予測するものでもありません。

CadDocumentInfo 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | ドキュメントの作成日です。 |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | ドキュメントの形式です。 |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | CAD ドキュメントの高さ。 |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | ドキュメント内のレイヤー。 |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | ドキュメント内のレイアウト。 |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | ドキュメントのページ数です。 |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | 現在のドキュメント情報で取得可能なすべてのプロパティの列挙可能オブジェクトです。 |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | ドキュメントのサイズ（バイト単位）です。 |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | CAD ドキュメントの幅。 |

### 関連項目
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
