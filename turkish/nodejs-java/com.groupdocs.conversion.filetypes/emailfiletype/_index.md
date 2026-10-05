---
title: "EmailFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "E-posta uygulamaları tarafından e-posta mesajları, ekler, klasörler, adres defterleri vb. dahil olmak üzere çeşitli verileri depolamak için kullanılan E-posta dosya formatlarını tanımlar."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

E-posta uygulamaları tarafından e-posta mesajları, ekler, klasörler, adres defterleri vb. dahil olmak üzere çeşitli verileri depolamak için kullanılan E-posta dosya formatlarını tanımlar. Aşağıdaki dosya türlerini içerir: [Eml](../../com.groupdocs.conversion.filetypes/emailfiletype\#Eml), [Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype\#Emlx), [Msg](../../com.groupdocs.conversion.filetypes/emailfiletype\#Msg), [Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype\#Vcf). [Pst](../../com.groupdocs.conversion.filetypes/emailfiletype\#Pst). [Ost](../../com.groupdocs.conversion.filetypes/emailfiletype\#Ost). [Olm](../../com.groupdocs.conversion.filetypes/emailfiletype\#Olm). E-posta formatları hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/email
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmailFileType()](#EmailFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Msg](#Msg) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişi, randevu veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. |
| [Eml](#Eml) | EML dosya formatı, Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder. |
| [Emlx](#Emlx) | EMLX dosya formatı Apple tarafından uygulanmakta ve geliştirilmektedir. |
| [Vcf](#Vcf) | VCF (Virtual Card Format) ya da vCard, iletişim bilgilerini depolamak için dijital bir dosya formatıdır. |
| [Mbox](#Mbox) | MBox dosya formatı, elektronik posta mesajlarının bir koleksiyonunu içeren bir kapsayıcıyı temsil eden genel bir terimdir. |
| [Pst](#Pst) | .PST uzantılı dosyalar, çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyaları (Personal Storage Table olarak da bilinir) temsil eder. |
| [Ost](#Ost) | OST veya Offline Storage Files, Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder. |
| [Olm](#Olm) | .olm uzantılı bir dosya, Mac İşletim Sistemi için Microsoft Outlook dosyasıdır. |
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


MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişi, randevu veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/email/msg

### Eml {#Eml}
```
public static final EmailFileType Eml
```


EML dosya formatı, Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder. Neredeyse tüm e-posta istemcileri, RFC-822 Internet Message Format Standardına uyumu nedeniyle bu dosya formatını destekler. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/email/eml

### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


EMLX dosya formatı Apple tarafından uygulanmakta ve geliştirilmektedir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya formatını kullanır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/email/emlx

### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) ya da vCard, iletişim bilgilerini depolamak için dijital bir dosya formatıdır. Bu format, popüler bilgi değişim uygulamaları arasında veri alışverişi için yaygın olarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/email/vcf

### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


MBox dosya formatı, elektronik posta mesajları koleksiyonunu içeren bir konteyneri temsil eden genel bir terimdir. Mesajlar, ekleriyle birlikte konteyner içinde depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/email/mbox/

### Pst {#Pst}
```
public static final EmailFileType Pst
```


.PST uzantılı dosyalar, çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyalarını (aynı zamanda Kişisel Depolama Tablosu olarak da adlandırılır) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/email/pst

### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST veya Çevrimdışı Depolama Dosyaları, Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/email/ost

### Olm {#Olm}
```
public static final EmailFileType Olm
```


.olm uzantılı bir dosya, Mac İşletim Sistemi için bir Microsoft Outlook dosyasıdır. OLM dosyası e-posta mesajlarını, günlükleri, takvim verilerini ve diğer uygulama verilerini depolar. Bunlar, Windows İşletim Sistemi'nde Outlook tarafından kullanılan PST dosyalarına benzer. Ancak, Mac için Outlook tarafından oluşturulan OLM dosyaları Windows için Outlook'ta açılamaz. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/email/olm

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
