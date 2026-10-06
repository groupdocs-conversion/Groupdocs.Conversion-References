---
title: "groupdocs.conversion.fluent"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "groupdocs.conversion.fluent altındaki tipler."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


`groupdocs.conversion.fluent` altındaki tipler.

### Sınıflar
| Sınıf | Açıklama |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Dönüşüm sayfası tamamlandığında işlenir. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Dönüşüm tamamlanmasını ele alır veya dönüşümü yürütür. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Sayfa dönüşümü için `OnConversionFailed` ayarlandıktan sonra akıcı bir arayüz sağlar. `OnConversionCompleted` ayarlamaya veya `Convert`/`Compress` işlemine devam etmeye izin verir. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | `OnConversionCompleted` sayfa dönüşümü için ayarlandıktan sonra akıcı arayüzü temsil eder, `OnConversionFailed` yapılandırmasına veya `Convert`/`Compress` işlemine devam etmeye olanak tanır. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Yalnızca sayfa bazlı dönüşüm işleyicilerini ayarlamak için akıcı bir arayüz sağlar. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Sayfa dönüşüm işleyicilerini ayarlamak için akıcı bir arayüz sağlar. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Sayfa bazlı dönüşüm işleyicileri aşamasının düzleştirilmiş halini temsil eder. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | Sayfa bazlı dönüşüm seçeneklerini veya işleyici kurulumunu ayarlamak için akıcı arayüz. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Dönüşüm tamamlandığında işlenir. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Dönüşüm tamamlanmasını işleyin veya dönüşümü yürütün. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Tüm dönüşüm sonuçlarını tek bir arşive sıkıştırır. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Sıkıştırma tamamlandığında işlenir. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | `Compress(...)` sonrasında devam. `Convert` ile doğrudan ilerleyin; kalıtılan [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) artık kullanılmıyor — bunun yerine işleyiciyi giriş aşamasında [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) aracılığıyla kaydedin. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Dönüşümü yürütün. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Dönüşüm seçeneklerini temsil eder. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Bir dönüşüm için dönüşüm seçeneklerini, tamamlanma işleme veya yürütmeyi temsil eder. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Dönüşüm seçeneklerini, tamamlanma işleme veya yürütmeyi temsil eder. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Dönüşüm seçeneklerini temsil eder. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Sıkıştır veya dönüştür. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Dönüşüm için kaynağı ayarlar. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Kaynak belge bilgilerini alır, sayfa sayısı ve dosya türüne özgü diğer özellikler dahil. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Kaynak belge için olası dönüşümleri alır. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | `OnConversionFailed` ayarlandıktan sonra akıcı arayüzü temsil eder, `OnConversionCompleted` ayarlamaya veya `Convert`/`Compress` işlemine devam etmeye izin verir. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | `OnConversionCompleted` ayarlandıktan sonra akıcı bir arayüz sağlar, `OnConversionFailed` yapılandırmasına veya `Convert`/`Compress` işlemine devam etmeye olanak tanır. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Yalnızca dönüşüm işleyicilerini ayarlamak için akıcı bir arayüz sağlar. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Dönüşüm işleyicilerini ayarlamak için akıcı bir arayüz sağlar. `OnConversionCompleted` ve/veya `OnConversionFailed` öğelerini herhangi bir sırada, her birini en fazla bir kez ayarlamaya veya ikisini de atlamaya izin verir. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Dönüşüm işleyicileri aşamasının düzleştirilmiş halini temsil eder. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Kaynak belgenin şifre korumalı olup olmadığını kontrol eder. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Dönüşüm yükleme seçeneklerini temsil eder. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Yüklenmiş bir belgeyle ilgili dönüşüm yükleme seçeneklerini veya eylemleri temsil eder. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Yalnızca dönüşüm seçeneklerini ayarlamak için akıcı bir arayüz sağlar. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Dönüşüm seçeneklerini veya dönüşüm işleyici kurulumunu temsil eder. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Giriş aşamasında ( `Load` öncesinde) dönüşüm ayarlarını veya olayları yapılandır. |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Dönüşüm ayarlarını veya dönüşüm kaynağını temsil eder. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Yüklenmiş belgeyle olası eylemleri sağlar. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Dönüştürülen belgenin nasıl saklanacağını ayarlar. |
