---
title: "WithEvents"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換ライフサイクルイベントハンドラで開始するフルエントチェーンのエントリーステージバリアントです。WithSettingsgroupdocs.conversion/fluentconverter/withsettings と同じエントリーステージに位置し、結果として得られる ConversionEventsgroupdocs.conversion/conversionevents バッグはコンバータによる各変換実行時に発火します。"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

変換ライフサイクルイベントハンドラで開始するフルエントチェーンのエントリーステージバリアントです。[`WithSettings`](../withsettings) と同じエントリーステージに位置し、結果として得られる [`ConversionEvents`](../../conversionevents) バッグはコンバータによる各変換実行時に発火します。

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| configure | Action`1 | イベントバッグを変更するアクション。 |

### 戻り値

`Load` をチェーンできるようにするソース選択段階です。

### 関連項目

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
