---
title: "Класс ImageConvertOptions"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Представляет параметры конвертации документа в тип файла изображения."
type: docs
url: /ru/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

Представляет параметры конвертации документа в тип файла изображения.

Тип ImageConvertOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | Инициализирует новый экземпляр ImageConvertOptions. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | Цвет фона, используемый там, где это поддерживается исходным форматом. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | Регулировка яркости изображения. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | Свойство ограничивает разрешение рендеринга PDF на страницу до нативного растрового разрешения страницы, предотвращая рендеринг с более высоким DPI, чем у встроенного изображения, и выводит страницу с её нативными (меньшими) размерами пикселей и DPI в конечном результате. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | Регулировка контраста, применяемая к изображению. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | Область обрезки растрового изображения после конвертации. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | Режим отражения изображения. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | Желаемый тип файла, в который следует преобразовать входной документ. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | Регулировка гаммы изображения. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | Опция, указывающая, следует ли преобразовать изображение в градации серого. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | Желаемая высота изображения после преобразования. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | Желаемое горизонтальное разрешение изображения после преобразования; по умолчанию используется разрешение входного файла или 96 dpi. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | Параметры преобразования, специфичные для JPEG. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | Нижняя граница по каждой оси, применяемая к ограниченному DPI рендеринга, когда включена опция [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/). |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | Номер страницы, с которой начинается конвертация. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | Список индексов страниц для конвертации. Должен быть указан для конвертации конкретных страниц. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | Количество страниц для конвертации, начиная с `PageNumber`. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | Параметры преобразования, специфичные для PSD. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | Угол поворота изображения. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Параметры преобразования, специфичные для Tiff. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | Свойство UsePdf. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | Желаемое вертикальное разрешение изображения после преобразования. Разрешение по умолчанию — разрешение входного файла или 96 dpi. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | Специфические параметры водяного знака. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | Параметры преобразования, специфичные для WebP. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | Желаемая ширина изображения после преобразования. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Guides
Руководства по задачам, использующие `ImageConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### См. также
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
