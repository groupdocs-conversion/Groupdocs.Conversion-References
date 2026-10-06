---
title: "IConversionHandlersStage クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "フラット化された変換ハンドラステージを表します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

フラット化された変換ハンドラステージを表します。

`OnConversionCompleted` または `OnConversionFailed` を任意の順序で、任意の回数設定でき、`Convert` / `Compress` に進む前に使用できます。イベントはこのステージではなく、[`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) を介して早期ステージで登録すべきです。

IConversionHandlersStage 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | 変換結果を圧縮します。 |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | 変換チェーンを実行します。 |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | ドキュメント変換が正常に完了したときに呼び出されるコールバックを登録し、再呼び出し時に以前に設定されたハンドラを置き換えます。 |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | ドキュメント変換が失敗したときに呼び出されるコールバックを登録します。 |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### 関連項目
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
