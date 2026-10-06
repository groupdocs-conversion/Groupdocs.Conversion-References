---
title: "IConversionByPageHandlerOnly sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Yalnızca sayfa bazlı dönüşüm işleyicilerini ayarlamak için akıcı bir arayüz sağlar."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Yalnızca sayfa bazlı dönüşüm işleyicilerini ayarlamak için akıcı bir arayüz sağlar.

`Convert`/`Compress` için [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) miras alır; aşamalı `OnConversion*` aşırı yüklemeleri, geriye uyumluluğu korumak için `new` anahtar kelimesiyle tutulur.

IConversionByPageHandlerOnly türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Dönüşüm sonuçlarını sıkıştırır; eski akıcı zincir yöntemini kullanmak yerine giriş aşamasında [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) aracılığıyla sıkıştırılmış akış işleyicisi kaydedin (`OnCompressionCompleted` ayarlanarak). |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Dönüştürme zincirini yürüt. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Bir sayfa dönüşümü başarıyla tamamlandığında çağrılacak bir geri aramayı kaydeder. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Bir sayfa dönüşümü başarısız olduğunda çağrılacak bir geri aramayı kaydeder. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### Ayrıca Bakınız
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
