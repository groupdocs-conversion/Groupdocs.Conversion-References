---
title: "OnFontSubstituted"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ソースドキュメントで参照されているフォントが利用できず、顧客提供の FontSubstitutegroupdocs.conversion.contracts/fontsubstitute ルール、設定されたデフォルトフォント、または変換パイプラインの内部フォールバックのいずれかで置き換えられたときに発生します。"
type: docs
weight: 80
url: /ja/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

ソースドキュメントで参照されているフォントが利用できず、（顧客提供の [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute) ルール、設定されたデフォルトフォント、または変換パイプラインの内部フォールバック）のいずれかで置き換えられたときに発生します。

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### 備考

このイベントは単一の `Converter.Convert(...)` 呼び出し内で `(SourceFileName, OriginalFontName)` ごとに重複除外されます — 購読者はソースドキュメントごとに欠落フォントにつき最大で1つの通知を受け取ります。変換スレッド上で同期的に発生します。画像変換では発生しません。

プレゼンテーションドキュメントの場合、フォント置換は Windows のみで検出されます。エンジンはプラットフォーム固有のフォントマッチングを介して解決するため、他の OS では利用できません。

### 関連項目

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
