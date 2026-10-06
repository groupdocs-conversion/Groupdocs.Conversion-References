---
title: "Свойство cap_resolution_to_page_content"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Это свойство ограничивает разрешение рендеринга PDF‑страницы до нативного растрового разрешения страницы, предотвращая рендеринг с более высоким DPI, чем у встроенного изображения, и выводя страницу в её нативном (меньшем) разрешении…"
type: docs
url: /ru/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

Свойство ограничивает разрешение рендеринга PDF на страницу до нативного растрового разрешения страницы, предотвращая рендеринг с более высоким DPI, чем у встроенного изображения, и выводит страницу с её нативными (меньшими) размерами пикселей и DPI в конечном результате.

Только страницы, доминирующие изображениями (скан), затрагиваются; страницы с текстом или векторным содержимым никогда не смягчаются и выводятся с запрошенным DPI. Ограничение игнорируется, когда задаётся явный вывод [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) или [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/). По умолчанию False (без ограничения; каждая страница рендерится и выводится с запрошенным DPI).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### См. также
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
