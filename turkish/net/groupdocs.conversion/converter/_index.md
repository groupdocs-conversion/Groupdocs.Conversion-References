---
title: Converter
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Belge dönüştürme sürecini kontrol eden ana sınıfı temsil eder.
type: docs
weight: 670
url: /tr/net/groupdocs.conversion/converter/
---
## Converter class

Belge dönüştürme sürecini kontrol eden ana sınıfı temsil eder.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Converter](converter#constructor)() | Yeni örneğini başlatır[`Converter`](../converter) akıcı dönüştürme kurulumu için sınıf. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_7)(string) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Yeni örneğini başlatır[`Converter`](../converter) sınıf. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(SaveDocumentStream, ConvertOptions) | Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(SaveDocumentStream, ConvertOptionsProvider) | Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(SaveDocumentStreamForFileType, ConvertOptions) | Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(SaveDocumentStreamForFileType, ConvertOptionsProvider) | Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(SavePageStream, ConvertOptions) | Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(SavePageStream, ConvertOptionsProvider) | Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(SavePageStreamForFileType, ConvertOptions) | Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(SavePageStreamForFileType, ConvertOptionsProvider) | Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) | Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) | Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) | Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) | Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(SavePageStream, ConvertedPageStream, ConvertOptions) | Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) | Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) | Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) | Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Kaynakları serbest bırakır. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Kaynak belge bilgilerini alır - sayfa sayısı ve dosya türüne özgü diğer belge özellikleri. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Kaynak belge için olası dönüşümleri alır. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Kaynak belge akışını yapılandırın |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Kaynak belge dizisini yapılandırın streams |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Dönüşüm için kaynak belgeyi yapılandırın |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Kaynak belgeler kümesini yapılandırın |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Dönüştürme ayarlarını yapılandırın |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Desteklenen tüm dönüşümleri alır |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Sağlanan belge uzantısı için desteklenen dönüştürmeleri alır |

### Ayrıca bakınız

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* ad alanı [GroupDocs.Conversion](../../groupdocs.conversion)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
