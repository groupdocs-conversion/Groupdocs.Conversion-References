---
title: "スライドショー"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "プレゼンテーションを Htmlgroupdocs.conversion.filetypes/webfiletype/html または Htmgroupdocs.conversion.filetypes/webfiletype/htm に変換する場合にのみ適用され、他のすべての変換では無視されます。プレゼンテーションがデフォルトの静的HTMLページではなく、スライド遷移とシェイプアニメーションを備えたインタラクティブなHTMLスライドショーになるかどうかを指定します。デフォルトは false です。"
type: docs
weight: 50
url: /ja/net/groupdocs.conversion.options.convert/webconvertoptions/slideshow/
---
## WebConvertOptions.SlideShow property

プレゼンテーションを [`Html`](../../../groupdocs.conversion.filetypes/webfiletype/html) または [`Htm`](../../../groupdocs.conversion.filetypes/webfiletype/htm) に変換する場合にのみ適用され、他のすべての変換では無視されます。プレゼンテーションがデフォルトの静的HTMLページではなく、スライド遷移とシェイプアニメーションを備えたインタラクティブなHTMLスライドショーになるかどうかを指定します。デフォルトは false です。

```csharp
public bool SlideShow { get; set; }
```

### 備考

結果は、スタイル、スクリプト、画像、フォント、メディアがインライン化された単一のHTMLファイルになります。スライドショーを駆動する2つのJavaScriptライブラリはCDNから読み込まれるため、ページをアニメーションさせたりナビゲートしたりするにはインターネット接続が必要です。

### 関連項目

* class [WebConvertOptions](../../webconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
