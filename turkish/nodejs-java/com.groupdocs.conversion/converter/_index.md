---
title: "Converter"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Belge dönüştürme sürecini kontrol eden ana sınıfı temsil eder."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Belge dönüştürme sürecini kontrol eden ana sınıfı temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Converter()](#Converter--) | Fluent dönüşüm kurulumu için class'ın yeni bir örneğini başlatır. |
| [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır. |
| [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır. |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır. |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır. |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | class'ın yeni bir örneğini başlatır. |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | class'ın yeni bir örneğini başlatır. |
| [Converter(String filePath)](#Converter-java.lang.String-) | Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır. |
| [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır. |
| [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır. |
| [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır. |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | class'ın yeni bir örneğini başlatır. |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | class'ın yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
| [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Kaynak belgeyi dönüştürür. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Kaynak belgeyi dönüştürür. |
| [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Kaynak belgeyi dönüştürür. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Kaynak belgeyi dönüştürür. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Kaynak belgeyi dönüştürür. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Kaynak belgeyi dönüştürür. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Kaynak belgeyi dönüştürür. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Kaynak belgeyi dönüştürür. |
| [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Kaynak belgeyi dönüştürür. |
| [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Kaynak belgeyi dönüştürür. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Kaynak belgeyi dönüştürür. |
| [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Kaynak belgeyi dönüştürür. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Kaynak belgeyi dönüştürür. |
| [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Kaynak belgeyi dönüştürür. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Kaynak belgeyi dönüştürür. |
| [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Kaynak belgeyi dönüştürür. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Kaynak belgeyi dönüştürür. |
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
| [getDocumentInfo()](#getDocumentInfo--) | Kaynak belge bilgilerini alır - sayfa sayısı ve dosya türüne özgü diğer belge özellikleri. |
| [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Kaynak belgenin şifre korumalı olup olmadığını kontrol eder. |
| [getPossibleConversions()](#getPossibleConversions--) | Kaynak belge için olası dönüşümleri alır. |
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Tüm desteklenen dönüşümleri alır **Learn more**Desteklenen dönüşümler hakkında daha fazla bilgi edinin: [Full list of supported conversions][]Mevcut dönüşümler hakkında daha fazla bilgi edinin: [How to get supported conversions in code][] |


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Sağlanan belge uzantısı için desteklenen dönüşümleri alır Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**Learn more**Desteklenen dönüşümler hakkında daha fazla bilgi edinin: [Full list of supported conversions][]Mevcut dönüşümler hakkında daha fazla bilgi edinin: [How to get supported conversions in code][] |


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
| [dispose()](#dispose--) | Kaynakları serbest bırakır. |
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Fluent dönüşüm kurulumu için class'ın yeni bir örneğini başlatır.  Örnek fluent dönüşüm kullanımı: `var converter = new Converter();` `converter .Load("") .ConvertTo("") .Convert();` `converter .WithSettings(() => new ConverterSettings()) .Load("").WithOptions(new PdfLoadOptions()) .ConvertTo("").WithOptions(new PdfConvertOptions()) .OnConversionCompleted(convertedDocumentStream => { }) .Convert();` `converter .Load("").WithOptions(new PdfLoadOptions()) .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions()) .OnConversionCompleted((number, stream) => {}) .Convert();` `converter.Load("").GetPossibleConversions(); converter.Load("").GetDocumentInfo(); converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions(); converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();`

### Converter(Supplier<InputStream> document) {#Converter-java.util.function.Supplier-java.io.InputStream--}
```
public Converter(Supplier<InputStream> document)
```


Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.util.function.Supplier<java.io.InputStream> | girdi akışı sağlayıcısı. |

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.util.function.Supplier<java.io.InputStream> | Bir giriş akışı sağlayıcısı. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Bir Dönüştürücü ayarları sağlayıcısı. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.util.function.Supplier<java.io.InputStream> | Bir giriş akışı sağlayıcısı. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Bir yükleme seçenekleri sağlayıcısı. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.util.function.Supplier<java.io.InputStream> | Bir giriş akışı sağlayıcısı. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Bir belge yükleme seçenekleri sağlayıcısı. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Bir Dönüştürücü ayarları sağlayıcısı. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Yeni bir sınıf örneği başlatır.**Daha fazla bilgi**FTP, Amazon S3 Storage, Windows Azure veya başka bir üçüncü taraf depolama alanında saklanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleme][]Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.util.function.Supplier<java.io.InputStream> | Bir giriş akışı sağlayıcısı. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Belge yükleme seçeneklerini döndüren işlev. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


Yeni bir sınıf örneği başlatır.**Daha fazla bilgi**FTP, Amazon S3 Storage, Windows Azure veya başka bir üçüncü taraf depolama alanında saklanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleme][]Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.util.function.Supplier<java.io.InputStream> | Okunabilir akışı döndüren bir sağlayıcı. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Belge yükleme seçeneklerini döndüren bir işlev. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Bir Dönüştürücü ayarları sağlayıcısı. |

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Kaynak belgeye giden dosya yolu. |

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Kaynak belgeye giden dosya yolu. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Bir Dönüştürücü ayarları sağlayıcısı. |

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Kaynak belgeye giden dosya yolu. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Yükleme seçenekleri sağlayıcısı. |

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Fluent dönüşüm kurulumu için [Converter](../../com.groupdocs.conversion/converter) sınıfının yeni bir örneğini başlatır.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Kaynak belgeye giden dosya yolu. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Belge yükleme seçenekleri sağlayıcısı. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Dönüştürücü ayarları sağlayıcısı. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Yeni bir sınıf örneği başlatır.**Daha fazla bilgi**FTP, Amazon S3 Storage, Windows Azure veya başka bir üçüncü taraf depolama alanında saklanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleme][]Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Kaynak belgeye giden dosya yolu. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Belge yükleme seçenekleri işlevi. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


Yeni bir sınıf örneği başlatır.**Daha fazla bilgi**FTP, Amazon S3 Storage, Windows Azure veya başka bir üçüncü taraf depolama alanında saklanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleme][]Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Kaynak belgeye giden dosya yolu. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Belge yükleme seçenekleri işlevi. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Dönüştürücü ayarları sağlayıcısı. |

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vendor | java.lang.String |  |
| version | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Çıktı akışı sağlayıcısı. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder. **Daha fazla bilgi**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Gelişmiş ayarlarla belge dönüştür][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | çıktı akışı sağlayıcısı |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | dönüştürülmüş belge akışını alan temsilci. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | istenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Kaynak belgeyi dönüştürür. Tam dönüştürülmüş belgeyi kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Çıktı akışı sağlayıcısı. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Dönüştürme seçenekleri sağlayıcı. Her dönüşüm için istenen hedef belge türüne özgü dönüştürme seçeneklerini sağlamak üzere çağrılır. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Kaynak belgeyi dönüştürür. Tam dönüştürülmüş belgeyi kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Çıktı akışı sağlayıcısı. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Dönüştürülmüş belge akışını alan temsilci. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Dönüştürme seçenekleri sağlayıcı. Her dönüşüm için istenen hedef belge türüne özgü dönüştürme seçeneklerini sağlamak üzere çağrılır. |

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Kaynak belgeyi dönüştürür. Tam dönüştürülmüş belgeyi kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Çıktı akışı işlevi. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Kaynak belgeyi dönüştürür. Tam dönüştürülmüş belgeyi kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Çıktı akışı işlevi |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Dönüştürülmüş belge akışını alan temsilci |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri |

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Kaynak belgeyi dönüştürür. Tam dönüştürülmüş belgeyi kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Çıktı akışı işlevi. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Dönüştürme seçenekleri sağlayıcı. Her dönüşüm için istenen hedef belge türüne özgü dönüştürme seçeneklerini sağlamak üzere çağrılır. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Kaynak belgeyi dönüştürür. Tam dönüştürülmüş belgeyi kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Çıktı akışı işlevi. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Dönüştürülmüş belge akışını alan temsilci. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Dönüştürme seçenekleri sağlayıcı. Her dönüşüm için istenen hedef belge türüne özgü dönüştürme seçeneklerini sağlamak üzere çağrılır. |

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Kaynak belgeye giden dosya yolu. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Sayfa çıktı akışı işlevi. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder. **Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Çıktı akışı işlevi. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Dönüştürülmüş belge sayfa akışını alan temsilci. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Çıktı akışı işlevi. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Dönüştürme seçenekleri sağlayıcı. Her dönüşüm için istenen hedef belge türüne özgü dönüştürme seçeneklerini sağlamak üzere çağrılır. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Çıktı akışı işlevi. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Dönüştürülmüş belge sayfa akışını alan temsilci. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Dönüştürme seçenekleri sağlayıcı. Her dönüşüm için istenen hedef belge türüne özgü dönüştürme seçeneklerini sağlamak üzere çağrılır. |

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Bir çıktı akışı işlevi. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Bir çıktı akışı işlevi. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Dönüştürülmüş belge sayfa akışını alan temsilci. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Bir çıktı akışı işlevi. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Dönüştürme seçenekleri sağlayıcı. Her dönüşüm için istenen hedef belge türüne özgü dönüştürme seçeneklerini sağlamak üzere çağrılır. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.**Daha fazla bilgi edinin**Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [How to convert document in 3 steps][]Dönüştürme kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Bir çıktı akışı işlevi. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Dönüştürülmüş belge sayfa akışını alan temsilci. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Dönüştürme seçenekleri sağlayıcı. Her dönüşüm için istenen hedef belge türüne özgü dönüştürme seçeneklerini sağlamak üzere çağrılır. |

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Kaynak belge bilgilerini alır - sayfa sayısı ve dosya türüne özgü diğer belge özellikleri.

**Learn more**Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info][]


[How to get document info]: https://docs.groupdocs.com/display/conversionnet/Get+document+info

**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info
### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Kaynak belgenin şifre korumalı olup olmadığını kontrol eder.

**Returns:**
boolean - belge şifre korumalıysa doğru **Daha fazla bilgi edinin**Dönüştürülmüş belge hakkında daha fazla bilgi - dosya türü, sayfa sayısı, oluşturma tarihi ve birçok diğer format özel özelliği: [How to check is the document password protected][]


[How to check is the document password protected]: https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected
### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Kaynak belge için olası dönüşümleri alır.

**Learn more**Learn more about supported conversions: [Full list of supported conversions][]Learn more about available conversions: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Tüm desteklenen dönüşümleri alır **Learn more**Desteklenen dönüşümler hakkında daha fazla bilgi edinin: [Full list of supported conversions][]Mevcut dönüşümler hakkında daha fazla bilgi edinin: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - desteklenen dönüşümler
### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Sağlanan belge uzantısı için desteklenen dönüşümleri alır Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**Learn more**Desteklenen dönüşümler hakkında daha fazla bilgi edinin: [Full list of supported conversions][]Mevcut dönüşümler hakkında daha fazla bilgi edinin: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uzantı | java.lang.String | Belge uzantısı |

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### dispose() {#dispose--}
```
public final void dispose()
```


Kaynakları serbest bırakır.

### close() {#close--}
```
public void close()
```




