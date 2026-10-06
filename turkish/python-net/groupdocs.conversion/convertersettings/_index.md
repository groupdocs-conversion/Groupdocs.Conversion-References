---
title: "ConverterSettings sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Converter davranışını özelleştirmek için ayarları tanımlar."
type: docs
url: /tr/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Converter davranışını özelleştirmek için ayarları tanımlar.

ConverterSettings türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | ConverterSettings'in varsayılan değerlerle yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | Dönüştürme sonuçlarını depolamak için kullanılan önbellek uygulaması. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | Özel yazı tipi dizin yolları. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | Dönüştürücü dinleyici uygulaması, dönüşüm durumu ve ilerlemesini izlemek için kullanılır; Started, Progress ve Completed geri çağırmaları, [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), ve [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) adreslerine, [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) oluşturulması sırasında yönlendirilir. |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | Dönüştürme sürecini kaydetmek için kullanılan günlükçü uygulaması. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | Sıkıştırma tamamlandığında olay işleyicisi. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | Sayfa bazında dönüşüm başarısız olduğunda tetiklenen olay işleyicisi. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | Bir dönüşüm başarısız olduğunda tetiklenen olay işleyicisi. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | Dönüştürücü, True olarak ayarlandığında yazı tipi dizinlerini özyinelemeli tarar. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | Dönüştürme için kullanılan geçici klasör. |

### Örnek

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Ayrıca Bakınız
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
