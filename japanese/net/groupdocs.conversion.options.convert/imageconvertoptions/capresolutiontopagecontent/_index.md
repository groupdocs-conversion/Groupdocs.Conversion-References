---
title: "CapResolutionToPageContent"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "設定されている場合、ページごとの PDF レンダリング解像度をページのネイティブラスタ解像度に制限し、ページが埋め込まれた画像が実際に持つ DPI より高い DPI でレンダリングされないようにします。その結果、要求された DPI に再拡大する代わりに、ページは元の小さいピクセルサイズとネイティブ DPI で最終出力に出力されます。画像主体のスキャンページのみが対象となり、テキストやベクターコンテンツを含むページは決してソフト化されず、要求された DPI で出力されます。明示的な出力 Widthgroupdocs.conversion.options.convert/imageconvertoptions/width または Heightgroupdocs.conversion.options.convert/imageconvertoptions/height が設定されている場合はスキップされます。デフォルトは false（制限なし）で、すべてのページが要求された DPI でレンダリングおよび出力されます。"
type: docs
weight: 40
url: /ja/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

設定されている場合、ページごとの PDF レンダリング解像度をページのネイティブラスタ解像度に制限し、ページが埋め込まれた画像が実際に持つ DPI より高い DPI でレンダリングされないようにします。その結果、要求された DPI に再拡大する代わりに、ページは元の（小さい）ピクセルサイズとネイティブ DPI で最終出力に出力されます。画像主体（スキャン）ページのみが対象となり、テキストやベクターコンテンツを含むページは決してソフト化されず、要求された DPI で出力されます。明示的な出力 [`Width`](../width) または [`Height`](../height) が設定されている場合はスキップされます。デフォルトは `false`（制限なし；すべてのページが要求された DPI でレンダリングおよび出力されます）。

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### 関連項目

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
