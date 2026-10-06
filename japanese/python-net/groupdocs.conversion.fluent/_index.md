---
title: "groupdocs.conversion.fluent"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "groupdocs.conversion.fluent 以下の型。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


`groupdocs.conversion.fluent` 以下の型。

### クラス
| クラス | 説明 |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | 変換ページ完了を処理します。 |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | 変換完了を処理するか、変換を実行します。 |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | ページ変換のために `OnConversionFailed` が設定された後に流暢なインターフェイスを提供します。`OnConversionCompleted` を設定するか、`Convert`/`Compress` に進むことができます。 |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | `OnConversionCompleted` がページ変換のために設定された後の流暢なインターフェイスを表します。`OnConversionFailed` の構成や `Convert`/`Compress` への進行が可能です。 |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | ページ単位の変換ハンドラのみを設定するための流暢なインターフェイスを提供します。 |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | ページ変換ハンドラを設定するための流暢なインターフェイスを提供します。 |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | フラット化されたページ単位の変換ハンドラステージを表します。 |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | ページ単位の変換オプションまたはハンドラ設定を行うための流暢なインターフェイスです。 |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | 変換完了を処理します。 |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | 変換完了を処理するか、変換を実行します。 |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | すべての変換結果を単一のアーカイブに圧縮します。 |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | 圧縮完了を処理します。 |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | `Compress(...)` の後の継続です。`Convert` を直接実行してください。継承された [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) は廃止予定です — 代わりにエントリ段階で [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) を使用してハンドラを登録してください。 |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | 変換を実行します。 |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | 変換オプションを表します。 |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | 変換のオプション、完了処理、または実行を表します。 |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | 変換オプション、完了処理、または実行を表します。 |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | 変換オプションを表します。 |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | 圧縮または変換します。 |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | 変換用のソースを設定します。 |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | ページ数やファイルタイプ固有のその他のプロパティを含む、ソースドキュメント情報を取得します。 |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | ソースドキュメントの可能な変換を取得します。 |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | `OnConversionFailed` が設定された後の流暢なインターフェイスを表します。`OnConversionCompleted` を設定するか、`Convert`/`Compress` に進むことができます。 |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | `OnConversionCompleted` が設定された後の流暢なインターフェイスを提供します。`OnConversionFailed` の構成や `Convert`/`Compress` への進行が可能です。 |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | 変換ハンドラのみを設定するための流暢なインターフェイスを提供します。 |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | 変換ハンドラを設定するための流暢なインターフェイスを提供します。`OnConversionCompleted` および/または `OnConversionFailed` を任意の順序で、各最大一回設定するか、両方をスキップすることができます。 |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | フラット化された変換ハンドラステージを表します。 |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | ソースドキュメントがパスワードで保護されているかどうかを確認します。 |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | 変換ロードオプションを表します。 |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | ロードされたドキュメントに対する変換ロードオプションまたはアクションを表します。 |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | 変換オプションのみを設定するための流暢なインターフェイスを提供します。 |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | 変換オプションまたは変換ハンドラの設定を表します。 |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | エントリ段階（`Load` の前）で変換設定またはイベントを設定します。 |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | 変換設定または変換ソースを表します。 |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | ロードされたドキュメントに対する可能なアクションを提供します。 |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | 変換されたドキュメントの保存方法を設定します。 |
