---
title: "FontSubstitutionContext クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ソースドキュメントの読み込みまたはレンダリング中に発生した単一のフォント代替について説明します。"
type: docs
url: /ja/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

ソースドキュメントの読み込みまたはレンダリング中に発生した単一のフォント代替について説明します。

インスタンスは [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) に渡されます。

FontSubstitutionContext 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | 新しい FontSubstitutionContext を初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | ソースドキュメントで参照されているが変換パイプラインで利用できないフォントの名前。 |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | 変換パイプラインが報告した置換メッセージをそのまま、逐語的かつ未解析で提供します。 |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | 変換対象のソースドキュメントのファイル名。ソースが `io.RawIOBase` ではないストリームとして提供された場合、実際のファイル名の代わりに生成された識別子が含まれます。 |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | 代替として使用されるフォントの名前です。エンジンが置換を記述テキストとしてのみ報告するドキュメントの場合、None になることがあります。その場合は [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) を参照してください。 |

### 関連項目
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
