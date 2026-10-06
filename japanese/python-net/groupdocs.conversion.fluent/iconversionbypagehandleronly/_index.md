---
title: "IConversionByPageHandlerOnly クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ページ単位の変換ハンドラのみを設定するための流暢なインターフェイスを提供します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

ページ単位の変換ハンドラのみを設定するための流暢なインターフェイスを提供します。

`Convert`/`Compress` 用に [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) を継承します。ステージ化された `OnConversion*` のオーバーロードは、後方互換性を保つために `new` キーワードで保持されます。

IConversionByPageHandlerOnly 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | 変換結果を圧縮します；エントリーステージで [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) を介して圧縮ストリームハンドラを登録します（`OnCompressionCompleted` を設定）。廃止された流暢なチェーンメソッドの使用は避けてください。 |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | 変換チェーンを実行します。 |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | ページ変換が正常に完了したときに呼び出されるコールバックを登録します。 |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | ページ変換が失敗したときに呼び出されるコールバックを登録します。 |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### 関連項目
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
