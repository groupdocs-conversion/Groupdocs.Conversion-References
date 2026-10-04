---
title: "IMarkdownImageSavingCallback"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Markdown に保存する際の画像のカスタム処理を扱います。画像ごとに一度呼び出され、MarkdownImageSavingArgs./markdownimagesavingargs を変更して、Markdown 出力に埋め込まれる URI を制御したり、画像バイトの書き込み先をリダイレクトしたりします。"
type: docs
weight: 1870
url: /ja/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

Markdown に保存する際の画像のカスタム処理を扱います。画像ごとに一度呼び出され、[`MarkdownImageSavingArgs`](../markdownimagesavingargs) を変更して、Markdown 出力に埋め込まれる URI を制御したり、画像バイトの書き込み先をリダイレクトしたりします。

```csharp
public interface IMarkdownImageSavingCallback
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | Markdown ドキュメントに書き込まれる各画像に対して呼び出されます。 |

### 例

シナリオ 1 — 画像バイトをメモリ内で取得し、プレースホルダー ID を埋め込む（呼び出し元が画像を別の場所に保存したり、後処理したりしたい場合に便利です）：

```csharp
class CaptureImagesCallback : IMarkdownImageSavingCallback
{
    private int _index;
    private readonly Dictionary<string, MemoryStream> _images;

    public CaptureImagesCallback(Dictionary<string, MemoryStream> images) => _images = images;

    public void ImageSaving(MarkdownImageSavingArgs args)
    {
        var id = $"image{_index++}";
        var buffer = new MemoryStream();
        _images[id] = buffer;
        args.ImageStream = buffer;            // redirect image bytes into our buffer
        args.ImageFileName = id;              // placeholder URI written into the .md
        args.KeepImageStreamOpen = true;      // keep buffer readable after Convert() returns
    }
}

var captured = new Dictionary<string, MemoryStream>();
try
{
    var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
    options.MarkdownOptions.ImageSavingCallback = new CaptureImagesCallback(captured);

    using var converter = new Converter("source.pdf");
    converter.Convert("output.md", options);
    // captured[\"image0\"], captured[\"image1\"], ... が画像バイトを保持しています
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

シナリオ 2 — .md と同じディスク上に画像を保存し、ファイル名で参照する：

```csharp
class FileImagesCallback : IMarkdownImageSavingCallback
{
    private readonly string _outputFolder;
    private int _index;

    public FileImagesCallback(string outputFolder) => _outputFolder = outputFolder;

    public void ImageSaving(MarkdownImageSavingArgs args)
    {
        var fileName = $"image{_index++}.png";
        args.ImageStream = new FileStream(Path.Combine(_outputFolder, fileName), FileMode.Create);
        args.ImageFileName = fileName;        // written into the .md as ![](image0.png)
        // KeepImageStreamOpen がデフォルト（false）のまま残っていると、コンバータはフラッシュしてファイルを閉じます。
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... がコンバータによって書き込まれ、閉じられます。
```

### 関連項目

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
