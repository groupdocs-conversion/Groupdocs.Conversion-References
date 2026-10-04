---
title: "IConversionFrom"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換のためのソースを設定する"
type: docs
weight: 1440
url: /ja/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

変換のためのソースを設定する

```csharp
public interface IConversionFrom
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | ソースドキュメントのストリームを設定する |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | ソースドキュメントのストリーム配列を設定する |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | ソースドキュメントのファイル名を設定する |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | ソースドキュメント配列を設定する |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | コンバータのライフタイム中に存在し、各変換実行時に発火する [`ConversionEvents`](../../groupdocs.conversion/conversionevents) バッグ上で変換ライフサイクルイベントハンドラを登録します。[`WithSettings`](../iconversionsettings/withsettings) の前後で呼び出すことができます。複数回の呼び出しは蓄積され、同じ内部バッグが各 *configure* アクションに渡されるため、後の呼び出しで上書きされない限り、以前の呼び出しで設定されたハンドラは残ります。 |

### 関連項目

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
