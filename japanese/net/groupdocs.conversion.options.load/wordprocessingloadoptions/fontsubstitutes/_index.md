---
title: "FontSubstitutes"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "WordsProcessing ドキュメントを変換する際に特定のフォントを置き換えます。"
type: docs
weight: 150
url: /ja/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes/
---
## WordProcessingLoadOptions.FontSubstitutes property

WordsProcessing ドキュメントを変換する際に特定のフォントを置き換えます。

```csharp
public IList<FontSubstitute> FontSubstitutes { get; set; }
```

### 備考

**Note:** The order of substitution is as follows:

1) フォント名に基づいて欠落しているフォントを自動的に置き換えます（有効な場合）。

2) FontConfig に基づいて欠落しているフォントを自動的に置き換えます（有効な場合）。

3) FontSubstitutes に基づいて欠落しているフォントを置き換えます（設定されている場合）。

4) FontInfo に基づいて欠落しているフォントを自動的に置き換えます（有効な場合）。

5) DefaultFont に基づいて欠落しているフォントを置き換えます（設定されている場合）。

### 関連項目

* class [FontSubstitute](../../../groupdocs.conversion.contracts/fontsubstitute)
* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
