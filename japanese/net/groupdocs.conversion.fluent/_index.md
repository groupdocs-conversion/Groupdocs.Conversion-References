---
title: "GroupDocs.Conversion.Fluent"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "この名前空間は、フルエント変換のためのインターフェイスを提供します。"
type: docs
weight: 60
url: /ja/net/groupdocs.conversion.fluent/
---
この名前空間は、フルエント変換のためのインターフェイスを提供します。

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | 変換ページが完了したことを処理する |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | 変換完了を処理するか、変換を実行する |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | ページ単位の変換ハンドラのみを設定するためのフルエントインターフェイス。ハンドラは[`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage)を通じて登録されます。 |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | ページ単位の変換ハンドラステージを平坦化したもの。[`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage)のページごとのミラーです。 |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | ページ単位の変換オプションまたはハンドラ設定を行うためのフルエントインターフェイス。オプションまたはハンドラを任意の順序で設定できますが、各々は一度だけ、または両方をスキップすることも可能です。 |
| [IConversionCompleted](./iconversioncompleted) | 変換完了を処理する |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | 変換完了を処理するか、変換を実行する |
| [IConversionCompressResult](./iconversioncompressresult) | すべての変換結果を単一のアーカイブに圧縮できます |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | `Compress(...)` の後の継続。`Convert` を続行します；エントリーステージで[`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents)を使用して圧縮ストリームハンドラを登録します。 |
| [IConversionConvert](./iconversionconvert) | 変換を実行する |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | 変換オプション |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | 変換オプションまたは変換完了または実行 |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | 変換オプションまたは変換完了または実行 |
| [IConversionConvertOptions](./iconversionconvertoptions) | 変換オプション |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | 圧縮または変換 |
| [IConversionFrom](./iconversionfrom) | 変換のためのソースを設定する |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | ソースドキュメント情報を取得します - ページ数やファイルタイプ固有のその他のドキュメントプロパティ。 |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | ソースドキュメントの可能な変換を取得します。 |
| [IConversionHandlerOnly](./iconversionhandleronly) | 変換ハンドラのみを設定するためのフルエントインターフェイス。ハンドラは[`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage)を通じて登録されます。 |
| [IConversionHandlersStage](./iconversionhandlersstage) | 変換ハンドラステージを平坦化したもの。`Convert` / `Compress` に進む前に、`OnConversionCompleted` または `OnConversionFailed` を任意の順序で、任意の回数設定できます。このステージではなく、早期段階で[`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents)を使用してイベントを登録すべきです。 |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | ソースドキュメントがパスワードで保護されているか確認します。 |
| [IConversionLoadOptions](./iconversionloadoptions) | 変換ロードオプション |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | 変換ロードオプションまたはロードされたドキュメントでのアクション |
| [IConversionOptionsOnly](./iconversionoptionsonly) | 変換オプションのみを設定するためのフルエントインターフェイス。 |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | 変換オプションまたは変換ハンドラ設定。 |
| [IConversionSettings](./iconversionsettings) | `Load` の前のエントリーステージで変換設定またはイベントを設定します。 |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | 変換設定または変換ソース |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | ロードされたドキュメントで可能なアクションを提供します。 |
| [IConversionTo](./iconversionto) | 変換されたドキュメントの保存方法を設定する |

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
