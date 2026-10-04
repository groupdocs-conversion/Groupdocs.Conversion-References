---
title: "WithEvents"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "コンバータのライフタイム全体で存続し、各変換実行時に発火する ConversionEventsgroupdocs.conversion/conversionevents バッグ上に変換ライフサイクルイベントハンドラを登録します。エントリ段階は WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings と同じです。複数回呼び出すと同じ内部バッグが各 configure アクションに渡され、以前の呼び出しで設定されたハンドラは後の呼び出しで上書きされない限り残ります。"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

コンバータのライフタイム全体で存続し、各変換実行時に発火する [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) バッグ上に変換ライフサイクルイベントハンドラを登録します。エントリ段階は [`WithSettings`](../withsettings) と同じです。複数回呼び出すと、同じ内部バッグが各 *configure* アクションに渡され、以前の呼び出しで設定されたハンドラは後の呼び出しで上書きされない限り残ります。

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| configure | Action`1 | イベントバッグを変更するアクション。 |

### 戻り値

`Load` をチェーンできるようにするソース選択段階です。

### 関連項目

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
