---
title: "EmailFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "E-posta uygulamaları tarafından e-posta mesajları, ekler, klasörler, adres defterleri vb. dahil olmak üzere çeşitli verileri depolamak için kullanılan e-posta dosya formatlarını tanımlar."
type: docs
weight: 15
url: /tr/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

E-posta dosya formatlarını tanımlar; bu formatlar e-posta uygulamaları tarafından e-posta mesajları, ekler, klasörler, adres defterleri vb. çeşitli verileri depolamak için kullanılır.
Aşağıdaki dosya türlerini içerir:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
E-posta formatları hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/email).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Msg](#Msg) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişi, randevu veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. |
|
|  | [Eml](#Eml) | EML dosya formatı, Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder. |
|
|  | [Emlx](#Emlx) | EMLX dosya formatı Apple tarafından uygulanmakta ve geliştirilmektedir. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) veya vCard, iletişim bilgilerini depolamak için kullanılan dijital bir dosya formatıdır. |
|
|  | [Mbox](#Mbox) | MBox dosya formatı, elektronik posta mesajlarının bir koleksiyonu için bir kapsayıcıyı temsil eden genel bir terimdir. |
|
|  | [Pst](#Pst) | .PST uzantılı dosyalar, Outlook Kişisel Depolama Dosyalarını (Personal Storage Table olarak da adlandırılır) temsil eder ve çeşitli kullanıcı bilgilerini depolar. |
|
|  | [Ost](#Ost) | OST veya Çevrimdışı Depolama Dosyaları, Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrimdışı modda kullanıcının posta kutusu verilerini temsil eder. |
|
|  | [Olm](#Olm) | .olm uzantılı bir dosya, Mac İşletim Sistemi için bir Microsoft Outlook dosyasıdır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Serileştirme yapıcısı


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişi, randevu veya diğer görevleri depolamak için kullanılan bir dosya formatıdır.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


EML dosya biçimi, Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder. Neredeyse tüm e-posta istemcileri, bu dosya biçiminin RFC-822 Internet Message Format Standardına uyumu nedeniyle bu biçimi destekler.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


EMLX dosya biçimi Apple tarafından uygulanmış ve geliştirilmiştir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya biçimini kullanır.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) veya vCard, iletişim bilgilerini depolamak için kullanılan dijital bir dosya biçimidir. Bu biçim, popüler bilgi alışverişi uygulamaları arasında veri değişimi için yaygın olarak kullanılır.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


MBox dosya biçimi, elektronik posta mesajlarının bir koleksiyonu için bir kapsayıcıyı temsil eden genel bir terimdir. Mesajlar, ekleriyle birlikte kapsayıcı içinde depolanır.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


.PST uzantılı dosyalar, Outlook Kişisel Depolama Dosyalarını (Personal Storage Table olarak da adlandırılır) temsil eder ve çeşitli kullanıcı bilgilerini depolar. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST veya Çevrimdışı Depolama Dosyaları, Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrimdışı modda kullanıcının posta kutusu verilerini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


.olm uzantılı bir dosya, Mac İşletim Sistemi için bir Microsoft Outlook dosyasıdır. OLM dosyası e-posta mesajlarını, günlükleri, takvim verilerini ve diğer uygulama verilerini depolar. Bunlar, Windows İşletim Sistemi üzerinde Outlook tarafından kullanılan PST dosyalarına benzer. Ancak, Mac için Outlook tarafından oluşturulan OLM dosyaları Windows için Outlook'ta açılamaz. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/email/olm).


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
