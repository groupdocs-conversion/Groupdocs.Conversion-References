---
title: "ConversionEvents sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüşüm yaşam döngüsü olay işleyicilerini toplar."
type: docs
url: /tr/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Dönüşüm yaşam döngüsü olay işleyicilerini toplar.

Bir örneği, [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) yapıcısının `events` parametresine veya akıcı `WithEvents` metoduna geçirin.

Bu, artık kullanılmayan bireysel [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) işleyici özelliklerine tercih edilir.

ConversionEvents türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | Dönüştürme çıktısının sıkıştırması tamamlandığında tetiklenen olay. Yalnızca sıkıştırma boru hattını (LIB_ZIP) içeren derlemelerde çağrılır. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | Dönüştürme çalışması bittiğinde, başarı ya da başarısızlık gözetmeksizin bir kez tetiklenen olay. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | Yüzde olarak dönüşüm ilerlemesi (0–100), periyodik olarak tetiklenir. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | Herhangi bir belge işlenmeden önce, dönüşüm çalışmasının başlangıcında bir kez tetiklenen olay. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | Tam belge dönüşümü başarıyla tamamlandığında bir kez tetiklenen olay. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | Tam belge dönüşümü başarısız olduğunda bir kez tetiklenen olay. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | Kaynak belge tarafından başvurulan bir yazı tipi mevcut olmadığında ve ikame edildiğinde (ya müşteri tarafından sağlanan [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) kuralı, ya yapılandırılmış varsayılan yazı tipi, ya da dönüşüm hattının dahili geri dönüşü) tetiklenen olay. |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | Sayfa başına dönüşüm başarıyla tamamlandığında, sayfa başına bir kez tetiklenen olay. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | Sayfa başına dönüşüm başarısız olduğunda, sayfa başına bir kez tetiklenen olay. |

### Ayrıca Bakınız
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
