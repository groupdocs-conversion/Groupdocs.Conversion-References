---
title: "VideoConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ビデオタイプへの変換オプション。"
type: docs
weight: 2280
url: /ja/net/groupdocs.conversion.options.convert/videoconvertoptions/
---
## VideoConvertOptions class

ビデオタイプへの変換オプション。

```csharp
public sealed class VideoConvertOptions : ConvertOptions<VideoFileType>
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [VideoConvertOptions](videoconvertoptions)() | 新しいインスタンスを初期化します [`VideoConvertOptions`](../videoconvertoptions) クラス。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AudioFormat](../../groupdocs.conversion.options.convert/videoconvertoptions/audioformat) { get; set; } | 使用するオーディオ形式は何ですか |
| [ExtractAudioOnly](../../groupdocs.conversion.options.convert/videoconvertoptions/extractaudioonly) { get; set; } | true に設定すると、ビデオからオーディオを抽出します |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する際の希望ファイルタイプ |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | [`Format`](../iconvertoptions/format) を実装します |
| [FramesPerSecond](../../groupdocs.conversion.options.convert/videoconvertoptions/framespersecond) { get; set; } | フレームレート（FPS）。デフォルトは 30 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプションインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [VideoFileType](../../groupdocs.conversion.filetypes/videofiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
