---
title: "IConversionHandlersStage sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüşüm işleyicileri aşamasının düzleştirilmiş halini temsil eder."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Dönüşüm işleyicileri aşamasının düzleştirilmiş halini temsil eder.

`Convert` / `Compress` işlemine geçmeden önce `OnConversionCompleted` veya `OnConversionFailed` öğelerini herhangi bir sırayla ve istediğiniz sayıda ayarlamaya izin verir. Olaylar bu aşamada değil, erken aşamada [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) aracılığıyla kaydedilmelidir.

IConversionHandlersStage türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Dönüştürme sonuçlarını sıkıştırır. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Dönüştürme zincirini yürüt. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Bir belge dönüşümü başarıyla tamamlandığında çağrılacak bir geri arama kaydeder, yeniden çağırma sırasında daha önce ayarlanmış işleyiciyi değiştirir. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Bir belge dönüşümü başarısız olduğunda çağrılacak bir geri aramayı kaydeder. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### Ayrıca Bakınız
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
