---
title: "IConversionCompressResultCompletedOrConvert sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Compress(...) sonrası devam."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/
is_root: false
weight: 130
---


## IConversionCompressResultCompletedOrConvert class

`Compress(...)` sonrasında devam. `Convert` ile doğrudan ilerleyin; kalıtılan [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) artık kullanılmıyor — bunun yerine işleyiciyi giriş aşamasında [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) aracılığıyla kaydedin.

IConversionCompressResultCompletedOrConvert türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/convert/) | Dönüştürme zincirini yürüt. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/#compressed_document_stream) | Sıkıştırılmış bir belge akışını alır. Yalnızca `Compress(CompressionConvertOptions)` ayarlanmışsa tetiklenir. |
| [on_compression_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed_action/) |  |

### Ayrıca Bakınız
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
