---
title: "ImageConvertOptions sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir belgeyi görüntü dosya türüne dönüştürme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

Bir belgeyi görüntü dosya türüne dönüştürme seçeneklerini temsil eder.

ImageConvertOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | Yeni bir ImageConvertOptions örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | Kaynak formatın desteklediği durumlarda kullanılacak arka plan rengi. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | Görüntü parlaklık ayarı. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | Bu özellik, sayfa başına PDF render çözünürlüğünü sayfanın yerel raster çözünürlüğüyle sınırlar; gömülü görüntüden daha yüksek DPI'da render edilmesini önler ve sayfayı yerel (daha küçük) piksel boyutları ve DPI ile nihai çıktıda üretir. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | Görüntüye uygulanan kontrast ayarı. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | Dönüştürmeden sonraki raster görüntünün kırpma alanı. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | Görüntü çevirme modu. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | Giriş belgesinin dönüştürülmesi gereken istenen dosya türü. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | Görüntü gama ayarı. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | Görüntünün gri tonlamaya dönüştürülüp dönüştürülmeyeceğini gösteren seçenek. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | Dönüştürme sonrası istenen görüntü yüksekliği. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | Dönüştürme sonrası istenen görüntü yatay çözünürlüğü; varsayılan olarak giriş dosyasının çözünürlüğü veya 96 dpi. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | JPEG'e özgü dönüştürme seçenekleri. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | Kısıtlanmış render DPI'sine uygulanan eksen başına alt sınır, [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) etkin olduğunda. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | Dönüştürmeye başlanacak sayfa numarası. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | Dönüştürülecek sayfa indekslerinin listesi. Belirli sayfaları dönüştürmek için belirtilmelidir. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | `PageNumber` değerinden başlayarak dönüştürülecek sayfa sayısı. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | PSD'ye özgü dönüştürme seçenekleri. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | Görüntü döndürme açısı. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Tiff'e özgü dönüştürme seçenekleri. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | UsePdf özelliği. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | Dönüştürme sonrası istenen görüntü dikey çözünürlüğü. Varsayılan çözünürlük, giriş dosyasının çözünürlüğü veya 96 dpi'dir. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | Filigrana özgü seçenekler. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | WebP'ye özgü dönüştürme seçenekleri. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | Dönüştürme sonrası istenen görüntü genişliği. |

### Örnek

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
`ImageConvertOptions` kullanan görev kılavuzları:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### Ayrıca Bakınız
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
