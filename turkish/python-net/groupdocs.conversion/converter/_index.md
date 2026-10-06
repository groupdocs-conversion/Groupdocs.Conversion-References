---
title: "Converter sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Belge dönüşüm sürecini kontrol eden ana sınıfı temsil eder."
type: docs
url: /tr/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

Belge dönüşüm sürecini kontrol eden ana sınıfı temsil eder.

Converter türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Converter'ın yeni bir örneğini başlatır. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | Yeni bir [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) örneğini başlatır. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | Yeni bir [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) örneğini başlatır. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | Açık dönüşüm olaylarıyla yeni bir Converter'ı başlatır. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | Açık dönüşüm olaylarıyla yeni bir Converter örneğini başlatır. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | Yeni bir Converter örneğini başlatır. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | Yeni bir [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) örneğini başlatır. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | Yeni bir [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) sınıfının örneğini başlatır. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | Açık dönüşüm olaylarıyla yeni bir Converter'ı başlatır. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | Açık dönüşüm olaylarıyla yeni bir Converter'ı başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin tamamını kaydeder. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin bütününü kaydeder. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin bütününü kaydeder. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin bütününü kaydeder. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin bütününü kaydeder. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Kaynak belgeyi dönüştürür ve dönüştürülmüş belgeyi sayfa sayfa kaydeder. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Kaynak belgeyi dönüştürür ve dönüştürülmüş belgeyi sayfa sayfa kaydeder. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Kaynak belgeyi dönüştürür ve dönüştürülmüş belgeyi sayfa sayfa kaydeder. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Kaynak belgeyi dönüştürür ve dönüştürülmüş belgeyi sayfa sayfa kaydeder. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | Kaynakları serbest bırakır. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | Desteklenen tüm dönüşümleri alır. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | Sayfa sayısı ve dosya türüne özgü diğer özellikler dahil olmak üzere kaynak belge bilgilerini alır. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | Kaynak belge için olası dönüşümleri alır. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | Sağlanan belge uzantısı için desteklenen dönüşümleri alır. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | Kaynak belgenin şifre korumalı olup olmadığını kontrol eder. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
`Converter` kullanan görev kılavuzları:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### Ayrıca Bakınız
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
