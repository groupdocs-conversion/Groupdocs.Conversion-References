---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Image ファイルタイプへの変換オプションです。"
type: docs
weight: 1950
url: /ja/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Image ファイルタイプへの変換オプションです。

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | `[`ImageConvertOptions`](../imageconvertoptions)` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | ソース形式でサポートされている場合に背景色を設定します。 |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | 画像の明るさを調整します。 |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | 設定されている場合、ページごとの PDF レンダリング解像度をページのネイティブラスター解像度に制限し、埋め込まれた画像が実際に持つ DPI より高い DPI でページがレンダリングされないようにします。その結果、要求された DPI に拡大し直す代わりに、ページはネイティブ（小さい）ピクセルサイズとネイティブ DPI で最終出力に出力されます。画像主体（スキャン）ページのみが対象となり、テキストやベクターコンテンツを含むページは決してソフト化されず、要求された DPI で出力されます。明示的な出力 [`Width`](./width) または [`Height`](./height) が設定されている場合はスキップされます。デフォルトは `false`（制限なし；すべてのページが要求された DPI でレンダリングおよび出力されます）。 |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | 画像のコントラストを調整します。 |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | 変換後にラスタ画像領域を切り取ります。 |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | 画像のフリップモードです。 |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する際の希望ファイルタイプ |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | [`Format`](../iconvertoptions/format) を実装します |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | 画像のガンマを調整します。 |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | グレースケール画像に変換するかどうかを示します。 |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | 変換後の画像高さ（ピクセル）を指定します。 |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | 変換後の画像の水平解像度を指定します。デフォルトの解像度は入力ファイルの解像度または 96 dpi です。 |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | JPEG 固有の変換オプションです。 |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | `[`CapResolutionToPageContent`](./capresolutiontopagecontent)` が有効な場合に、制限されたレンダー DPI に適用される軸ごとの下限です。制限された DPI はこの値以下に下げられません。デフォルトは `0`（下限なし）です。 |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | [`PageNumber`](../ipagedconvertoptions/pagenumber) を実装します |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | [`Pages`](../ipagerangedconvertoptions/pages) を実装します |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | [`PagesCount`](../ipagedconvertoptions/pagescount) を実装します |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | PSD 固有の変換オプションです。 |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | 画像の回転角度です。 |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | TIFF 固有の変換オプションです。 |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | `true` の場合、入力は最初に PDF に変換され、その後目的の形式に変換されます。 |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | 変換後の画像の垂直解像度を指定します。デフォルトの解像度は入力ファイルの解像度または 96 dpi です。 |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | [`Watermark`](../iwatermarkedconvertoptions/watermark) を実装します |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | WebP 固有の変換オプションです。 |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | 変換後の画像幅（ピクセル）を指定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプションインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
