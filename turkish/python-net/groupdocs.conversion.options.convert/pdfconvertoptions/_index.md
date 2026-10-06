---
title: "PdfConvertOptions sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "PDF dosya türüne dönüştürme seçenekleri."
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

PDF dosya türüne dönüştürme seçenekleri.

PdfConvertOptions türü aşağıdaki üyeleri içerir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | Yeni bir [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | Dönüştürmeden sonraki istenen sayfa DPI'si. Varsayılan çözünürlük 96 dpi'dir. |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | Bu özellik, tam yazı tipi dosyasının bir alt küme yerine PDF'ye gömülüp gömülmeyeceğini belirler. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | Yedek sayfa boyutu. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | Giriş belgesinin dönüştürülmesi gereken istenen dosya türü. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | PDF dönüşümü sırasında uygulanan kenar boşluğu ayarları. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | Yönlendirme ayarları. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | Dönüştürmeye başlanacak sayfa numarası. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | Dönüştürülecek sayfa indekslerinin listesi; belirli sayfaları dönüştürmek için belirtin. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | `page_number` değerinden başlayarak dönüştürülecek sayfa sayısı. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | Dönüştürülen belgeyi korumak için kullanılan şifre. |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | PDF'ye özgü dönüştürme seçenekleri. |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | Yeniden boyutlandırma modu, sayfa boyutu değiştirildiğinde içeriğin nasıl ölçeklenmesi gerektiğini belirtir. Varsayılan AlignTopLeft'tir (ölçekleme yok). |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | Sayfa döndürmesi. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | PDF dönüşümü sırasında kullanılan sayfa boyutu ayarları. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | Filigrana özgü seçenekler. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
`PdfConvertOptions` kullanan görev kılavuzları:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Ayrıca Bakınız
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
