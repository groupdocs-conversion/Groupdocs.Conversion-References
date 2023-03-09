---
title: Converter
second_title: GroupDocs.Conversion for .NET API リファレンス
description: ドキュメント変換プロセスを制御するメイン クラスを表します
type: docs
weight: 730
url: /ja/net/groupdocs.conversion/converter/
---
## Converter class

ドキュメント変換プロセスを制御するメイン クラスを表します。

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Converter](converter#constructor)() | の新しいインスタンスを初期化します[`Converter`](../converter)流暢な変換設定のクラス. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_7)(string) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | の新しいインスタンスを初期化します[`Converter`](../converter)class. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | ソース ドキュメントを変換します。変換されたドキュメント全体を保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | ソース ドキュメントを変換します。変換されたドキュメント全体を保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | ソース ドキュメントを変換します。変換されたドキュメント全体を保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | ソース ドキュメントを変換します。変換されたドキュメント全体を保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | ソース ドキュメントを変換します。変換されたドキュメント全体を保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | ソース ドキュメントを変換します。変換されたドキュメント全体を保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | ソース ドキュメントを変換します。変換されたドキュメント全体を保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | ソース ドキュメントを変換します。変換されたドキュメント全体を保存します. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | ソース ドキュメントを変換します。変換されたドキュメント全体を保存します. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | リソースを解放します。 |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | ソース ドキュメント情報を取得します - ファイルの種類に固有のページ数とその他のドキュメント プロパティ. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | ソース ドキュメントの可能な変換を取得します。 |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | ソース ドキュメントを構成する stream |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | ソース ドキュメントのセットを構成する stream |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | conversion のソース ドキュメントを構成します |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | ソース ドキュメントのセットを構成する |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | 変換設定を構成する |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | サポートされているすべての変換を取得します |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | 提供されたドキュメント拡張子でサポートされている変換を取得します |

### 関連項目

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* 名前空間 [GroupDocs.Conversion](../../groupdocs.conversion)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
