---
title: "EmailFileType"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "E-posta uygulamaları tarafından e-posta mesajları, ekler, klasörler, adres defterleri vb. dahil olmak üzere çeşitli verileri depolamak için kullanılan e-posta dosya formatlarını tanımlar. Aşağıdaki dosya türlerini içerir: Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. E-posta formatları hakkında daha fazla bilgi edinin buradahttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /tr/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Email dosya formatlarını tanımlar; e-posta uygulamaları tarafından e-posta mesajları, ekler, klasörler, adres defterleri vb. gibi çeşitli verileri depolamak için kullanılır. Aşağıdaki dosya türlerini içerir: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). Email formatları hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/email) tıklayın.

```csharp
public sealed class EmailFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [EmailFileType](emailfiletype)() | Serileştirme yapıcısı |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dosya türü açıklaması |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Dosya uzantısı |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Dosya ailesi |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Dosya formatı |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Mevcut nesneyi diğerine karşılaştırır. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) uygular. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Dize temsili |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | EML dosya formatı, Outlook ve diğer ilgili uygulamalar kullanılarak kaydedilen e-posta mesajlarını temsil eder. Neredeyse tüm e-posta istemcileri, RFC-822 Internet Message Format Standardına uyumu nedeniyle bu dosya formatını destekler. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/email/eml) tıklayın. |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | EMLX dosya formatı Apple tarafından uygulanıp geliştirilmiştir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya formatını kullanır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/email/emlx) tıklayın. |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | ICS (iCalendar) dosya formatı, etkinlikler, yapılacaklar ve boş/meşgul verileri gibi takvim ve planlama bilgilerini temsil etmek ve değiştirmek için kullanılır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/email/ics) tıklayın. |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox dosya formatı, elektronik posta mesajlarının bir koleksiyonu için bir kapsayıcıyı temsil eden genel bir terimdir. Mesajlar, ekleriyle birlikte bu kapsayıcı içinde depolanır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/email/mbox/) tıklayın. |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişi, randevu veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/email/msg) tıklayın. |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | .olm uzantılı bir dosya, Mac İşletim Sistemi için Microsoft Outlook dosyasıdır. OLM dosyası e-posta mesajları, günlükler, takvim verileri ve diğer uygulama verilerini depolar. Bunlar, Windows İşletim Sistemi'nde Outlook tarafından kullanılan PST dosyalarına benzer. Ancak, Mac için Outlook tarafından oluşturulan OLM dosyaları Windows için Outlook'ta açılamaz. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/email/olm) tıklayın. |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST veya Offline Storage Files, Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/email/ost) tıklayın. |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | .PST uzantılı dosyalar, çeşitli kullanıcı bilgilerini depolayan Outlook Personal Storage Files (kişisel depolama tablosu olarak da bilinir) temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/email/pst) tıklayın. |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) veya vCard, iletişim bilgilerini depolamak için kullanılan dijital bir dosya formatıdır. Bu format, popüler bilgi değişim uygulamaları arasında veri alışverişi için yaygın olarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/email/vcf) tıklayın. |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
