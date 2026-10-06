---
title: "WordProcessingConvertOptions sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Kelime işlem dosya türüne dönüştürme seçenekleri."
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
is_root: false
weight: 620
---


## WordProcessingConvertOptions class

Kelime işlem dosya türüne dönüştürme seçenekleri.

WordProcessingConvertOptions türü aşağıdaki üyeleri ortaya çıkar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/) | Yeni bir [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi/) | Dönüştürmeden sonraki istenen sayfa DPI'si. Varsayılan çözünürlük 96 dpi'dir. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallback_page_size/) | Yedek sayfa boyutu. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/format/) | Giriş belgesinin dönüştürülmesi gereken istenen dosya türü. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/margin_settings/) | Dönüştürme için kenar boşluğu ayarları, [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/) tarafından temsil edilir. |
| [markdown_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdown_options/) | Markdown dönüştürme seçenekleri. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientation_settings/) | Yönlendirme ayarları. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/page_number/) | Dönüştürmeye başlanacak sayfa numarası. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages/) | Dönüştürülecek sayfa indekslerinin listesi. Belirli sayfaları dönüştürmek için belirtilmelidir. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages_count/) | `PageNumber` değerinden başlayarak dönüştürülecek sayfa sayısı. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/password/) | Dönüştürülen belgeyi korumak için kullanılan şifre. |
| [pdf_recognition_mode](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdf_recognition_mode/) | Dönüştürme için kullanılan PDF tanıma modu, [`IPdfRecognitionModeOptions.pdf_recognition_mode`](/conversion/python-net/groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions/pdf_recognition_mode/) uygulanarak sağlanır. |
| [rtf_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtf_options/) | RTF'ye özgü dönüştürme seçenekleri. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/size_settings/) | Dönüştürme için boyut ayarları. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/watermark/) | Filigrana özgü seçenekler. |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom/) | Yüzde olarak yakınlaştırma seviyesi. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Guides
`WordProcessingConvertOptions` kullanan görev kılavuzları:

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### Ayrıca Bakınız
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
