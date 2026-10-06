---
title: "WatermarkTextOptions sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürülen belgeye metin filigranı ekleme seçenekleri."
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/watermarktextoptions/
is_root: false
weight: 590
---


## WatermarkTextOptions class

Dönüştürülen belgeye metin filigranı ekleme seçenekleri.

Filigran görünümünün yapılandırmasını temsil eder. Aşağıdaki özellikler yapılandırılabilir:

- `text`: The text to be used for the watermark.
- `font`: The font name used for the watermark text.
- `color`: The color of the watermark text.
- `top`: The top offset of the watermark.
- `left`: The left offset of the watermark.
- `width`: The width of the watermark.
- `height`: The height of the watermark.
- `background`: Whether the watermark is rendered in the background.

WatermarkTextOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/#text) | Belirtilen filigran metniyle bir WatermarkTextOptions örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/clone/) | Mevcut örneği klonla. ([`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) üzerinden devralınmıştır) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | İki nesne örneğinin eşit olup olmadığını belirler. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Varsayılan hash işlevi olarak hizmet verir. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [color](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/color/) | Metin filigranı uygulandığında filigran yazı tipi rengi. |
| [text](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/text/) | Filigran metni. |
| [watermark_font](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/watermark_font/) | Metin filigranı uygulandığında kullanılan filigran yazı tipi. |
| [auto_align](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/auto_align/) | Filigran, True olarak ayarlandığında sayfa boyutuna otomatik olarak ölçeklendirilir. ([`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) üzerinden devralınmıştır) |
| [background](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/background/) | Filigran arka plan olarak damgalanır; True ise altta yer alır, aksi takdirde üstte yer alır (varsayılan False'tur). ([`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) üzerinden devralınmıştır) |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/height/) | Filigran yüksekliği. ([`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) üzerinden devralınmıştır) |
| [left](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/left/) | Filigranın sol konumu. ([`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) üzerinden devralınmıştır) |
| [rotation_angle](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/rotation_angle/) | Filigran döndürme açısı. ([`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) üzerinden devralınmıştır) |
| [top](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/top/) | Filigranın üst konumu. ([`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) üzerinden devralınmıştır) |
| [transparency](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/transparency/) | Filigran şeffaflığı. Değer 0 ile 1 arasında olmalıdır. Değer 0 tamamen görünür, değer 1 görünmezdir. ([`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) üzerinden devralınmıştır) |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/width/) | Filigran genişliği. ([`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) üzerinden devralınmıştır) |

### Örnek

```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

with Converter("./professional-services.docx") as converter:
    watermark = WatermarkTextOptions("DRAFT")
    watermark.color = Color.from_argb(128, 211, 211, 211)  # lite gray
    watermark.top = 10
    watermark.left = 10
    watermark.width = 300
    watermark.height = 300
    watermark.background = True

    options = PdfConvertOptions()
    options.pages_count = 1
    options.watermark = watermark

    converter.convert("./professional-services.pdf", options)
```

### Guides
`WatermarkTextOptions` kullanan görev kılavuzları:

* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)

### Ayrıca Bakınız
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
