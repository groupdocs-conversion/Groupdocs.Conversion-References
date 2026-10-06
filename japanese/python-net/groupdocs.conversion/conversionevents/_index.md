---
title: "ConversionEvents クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換ライフサイクルのイベントハンドラを集約します。"
type: docs
url: /ja/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

変換ライフサイクルのイベントハンドラを集約します。

インスタンスを [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) コンストラクタの `events` パラメータ、またはフルエントな `WithEvents` メソッドに渡します。

個別の [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) ハンドラプロパティ（廃止予定）よりもこちらを使用してください。

ConversionEvents 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | 変換出力の圧縮が完了したときに発火するイベントです。圧縮パイプライン（LIB_ZIP）を含むビルドでのみ呼び出されます。 |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | 変換実行が完了したときに一度だけ発生するイベントで、成功か失敗かに関係なく。 |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | 変換の進捗率（0〜100）をパーセンテージで示すイベントで、定期的に発生します。 |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | 変換実行の開始時に、一度だけ発生するイベントで、ドキュメントが処理される前に発火します。 |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | 全体ドキュメントの変換が正常に完了したときに、一度だけ発生するイベントです。 |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | 全体ドキュメントの変換が失敗したときに、一度だけ発生するイベントです。 |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | ソースドキュメントで参照されているフォントが利用できず、置き換えられたときに発生するイベント（顧客提供の[`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) ルール、設定されたデフォルトフォント、または変換パイプラインの内部フォールバックのいずれかによる）。 |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | ページ単位の変換が正常に完了したときに、ページごとに一度だけ発生するイベントです。 |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | ページ単位の変換が失敗したときに、ページごとに一度だけ発生するイベントです。 |

### 関連項目
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
