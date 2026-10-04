---
title: "CapResolutionToPageContent"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "При включении ограничивает разрешение рендеринга PDF на страницу до нативного растрового разрешения страницы, поэтому страница никогда не рендерится с более высоким DPI, чем фактически содержит её встроенное изображение, и выводит эту страницу в её нативных меньших пиксельных размерах и нативном DPI в окончательном выводе вместо увеличения до запрошенного DPI. Затрагиваются только сканированные страницы, доминирующие изображением; страницы с текстом или векторным содержимым никогда не смягчаются и выводятся с запрошенным DPI. Пропускается, когда явно задаётся вывод Widthgroupdocs.conversion.options.convert/imageconvertoptions/width или Heightgroupdocs.conversion.options.convert/imageconvertoptions/height. По умолчанию false — без ограничения; каждая страница рендерится и выводится с запрошенным DPI."
type: docs
weight: 40
url: /ru/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

При включении ограничивает разрешение рендеринга PDF на страницу до нативного растрового разрешения страницы, поэтому страница никогда не рендерится с более высоким DPI, чем фактически содержит её встроенное изображение, и выводит её в нативных (меньших) пиксельных размерах и нативном DPI в окончательном выводе вместо повторного увеличения до запрошенного DPI. Затрагиваются только страницы, доминирующие изображением (скан); страницы с текстом или векторным содержимым никогда не смягчаются и выводятся с запрошенным DPI. Пропускается, когда явно задаётся вывод [`Width`](../width) или [`Height`](../height). По умолчанию `false` (без ограничения; каждая страница рендерится и выводится с запрошенным DPI).

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### См. также

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
