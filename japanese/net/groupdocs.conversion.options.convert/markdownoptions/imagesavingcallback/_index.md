---
title: "ImageSavingCallback"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Markdown を保存する際に、画像ごとに一度コールバックが呼び出されます。呼び出し元が画像を外部に永続化し、ドキュメントに埋め込まれた URI を置き換えることができます。null でない場合、ExportImagesAsBase64groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64 より優先されます。"
type: docs
weight: 30
url: /ja/net/groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback/
---
## MarkdownOptions.ImageSavingCallback property

Markdown を保存する際に、画像ごとに一度コールバックが呼び出されます。呼び出し元が画像を外部に永続化し、ドキュメントに埋め込まれた URI を置き換えることができます。null でない場合、[`ExportImagesAsBase64`](../exportimagesasbase64) より優先されます。

```csharp
public IMarkdownImageSavingCallback ImageSavingCallback { get; set; }
```

### 関連項目

* interface [IMarkdownImageSavingCallback](../../imarkdownimagesavingcallback)
* class [MarkdownOptions](../../markdownoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
