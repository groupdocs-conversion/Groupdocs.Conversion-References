---
title: "IConversionHandlerCompleted クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "OnConversionFailed が設定された後のフルエントインターフェイスを表し、OnConversionCompleted の設定や Convert/Compress への進行を可能にします。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/
is_root: false
weight: 230
---


## IConversionHandlerCompleted class

`OnConversionFailed` が設定された後の流暢なインターフェイスを表します。`OnConversionCompleted` を設定するか、`Convert`/`Compress` に進むことができます。

IConversionHandlerCompleted 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/#options) | 変換結果を圧縮し、`Convert` に進む継続を返します。 |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/convert/) | 変換チェーンを実行します。 |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed/#on_completed) | ドキュメント変換が正常に完了したときに呼び出されるコールバックを登録します。 |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/#on_failed) | ドキュメント変換が失敗したときに呼び出されるコールバックを登録します。再度呼び出すと、以前に設定されたハンドラが置き換えられます。 |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed_action/) |  |

### 関連項目
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
