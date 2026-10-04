---
title: "WithEvents"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "コンバータのライフタイム中に存在し、各変換実行時に発火する ConversionEventsgroupdocs.conversion/conversionevents バッグ上で変換ライフサイクルイベントハンドラを登録します。WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings の前後で呼び出すことができます。複数回呼び出すと、同じ内部バッグが各 configure アクションに渡されるため、以前の呼び出しで設定されたハンドラは後の呼び出しで上書きされない限り残ります。"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion.fluent/iconversionfrom/withevents/
---
## IConversionFrom.WithEvents method

コンバータのライフタイム中に存在し、各変換実行時に発火する [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) バッグ上で変換ライフサイクルイベントハンドラを登録します。[`WithSettings`](../../iconversionsettings/withsettings) の前後で呼び出すことができます。複数回呼び出すと、同じ内部バッグが各 *configure* アクションに渡されるため、以前の呼び出しで設定されたハンドラは後の呼び出しで上書きされない限り残ります。

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| configure | Action`1 | イベントバッグを変更するアクション。 |

### 戻り値

このステージは、さらにエントリーステージの呼び出しや `Load` をチェーンできるようにします。

### 関連項目

* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
