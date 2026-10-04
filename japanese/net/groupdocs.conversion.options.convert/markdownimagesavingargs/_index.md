---
title: "MarkdownImageSavingArgs"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ImageSaving./imarkdownimagesavingcallback/imagesaving に渡される引数。"
type: docs
weight: 2000
url: /ja/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

[`ImageSaving`](../imarkdownimagesavingcallback/imagesaving) に渡される引数。

```csharp
public sealed class MarkdownImageSavingArgs
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | Markdown 出力の画像 URI に埋め込まれるファイル名（またはプレースホルダー ID）。割り当てることで URI を書き換えます。 |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | このコールバックが戻った後にコンバータが画像バイトを書き込む宛先ストリーム。独自の書き込み可能ストリームに置き換えてください（例: ディスク永続化用の FileStream や、後で読み取ることを想定した MemoryStream）。 |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | false（既定）の場合、コンバータは書き込み後に [`ImageStream`](./imagestream) を閉じます — ディスクにフラッシュすべき FileStream の置き換えに慣習的です。true に設定すると、変換完了後もストリームを開いたままにします（自分で読み取ることを想定した MemoryStream に典型的）。この場合、呼び出し側が破棄を管理します。 |

### 関連項目

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
