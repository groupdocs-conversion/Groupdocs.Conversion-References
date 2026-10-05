---
title: "WebFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Web belgelerini tanımlar."
type: docs
weight: 27
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Web belgelerini tanımlar. Aşağıdaki türleri içerir: [Xml](../../com.groupdocs.conversion.filetypes/webfiletype\#Xml), [Json](../../com.groupdocs.conversion.filetypes/webfiletype\#Json), [Html](../../com.groupdocs.conversion.filetypes/webfiletype\#Html), [Htm](../../com.groupdocs.conversion.filetypes/webfiletype\#Htm), [Mht](../../com.groupdocs.conversion.filetypes/webfiletype\#Mht), [Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype\#Mhtml), [Chm](../../com.groupdocs.conversion.filetypes/webfiletype\#Chm), Web formatları hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WebFileType()](#WebFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Xml](#Xml) | XML, nesneleri tanımlamak için etiketler kullanan, HTML'ye benzer ancak farklı bir yapı olan Extensible Markup Language (Genişletilebilir İşaretleme Dili) anlamına gelir. |
| [Json](#Json) | JSON (JavaScript Object Notation), verileri depolamak ve iletmek için insan tarafından okunabilir metin kullanan açık standart bir dosya formatıdır. |
| [Html](#Html) | HTML (Hyper Text Markup Language), tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. |
| [Htm](#Htm) | HTM (Hyper Text Markup Language), tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. |
| [Mht](#Mht) | MHTML uzantılı dosyalar, çeşitli uygulamalar tarafından oluşturulabilen bir web sayfası arşiv formatını temsil eder. |
| [Mhtml](#Mhtml) | MHTML uzantılı dosyalar, çeşitli uygulamalar tarafından oluşturulabilen bir web sayfası arşiv formatını temsil eder. |
| [Chm](#Chm) | CHM dosya formatı, bir dizi HTML sayfasından oluşan Microsoft HTML yardım dosyasını temsil eder. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Serileştirme yapıcısı

### Xml {#Xml}
```
public static final WebFileType Xml
```


XML, nesneleri tanımlamak için etiketler kullanan, HTML'ye benzer ancak farklı bir yapı olan Extensible Markup Language (Genişletilebilir İşaretleme Dili) anlamına gelir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/xml

### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation), verileri depolamak ve iletmek için insan tarafından okunabilir metin kullanan açık standart bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/web/json

### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language), tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/html

### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language), tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/html

### Mht {#Mht}
```
public static final WebFileType Mht
```


MHTML uzantılı dosyalar, çeşitli uygulamalar tarafından oluşturulabilen bir web sayfası arşiv formatını temsil eder. Bu format, web HTML kodunu ve ilişkili kaynakları tek bir dosyada sakladığı için arşiv formatı olarak bilinir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


MHTML uzantılı dosyalar, çeşitli uygulamalar tarafından oluşturulabilen bir web sayfası arşiv formatını temsil eder. Bu format, web HTML kodunu ve ilişkili kaynakları tek bir dosyada sakladığı için arşiv formatı olarak bilinir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Chm {#Chm}
```
public static final WebFileType Chm
```


CHM dosya formatı, bir dizi HTML sayfasından oluşan Microsoft HTML yardım dosyasını temsil eder. Konulara hızlı erişim ve yardım belgesinin farklı bölümlerine gezinme için bir indeks sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/web/chm

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Dosya türü için varsayılan dönüştürme seçenekleri hazırlandı

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
