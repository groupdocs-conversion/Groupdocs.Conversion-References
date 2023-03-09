---
title: EmailFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Eposta uygulamaları tarafından eposta mesajları ekler klasörler adres defterleri vb. dahil olmak üzere çeşitli verilerini depolamak için kullanılan Eposta dosya biçimlerini tanımlar. Aşağıdaki dosya türlerini içerirEml./emailfiletype/eml  Emlx./emailfiletype/emlx  Msg./emailfiletype/msg  Vcf./emailfiletype/vcf . Mbox./emailfiletype/mbox . Pst./emailfiletype/pst . Ost./emailfiletype/ost . Eposta biçimleri hakkında daha fazla bilgi edininBuradahttps//wiki.fileformat.com/email .
type: docs
weight: 920
url: /tr/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

E-posta uygulamaları tarafından e-posta mesajları, ekler, klasörler, adres defterleri vb. dahil olmak üzere çeşitli verilerini depolamak için kullanılan E-posta dosya biçimlerini tanımlar. Aşağıdaki dosya türlerini içerir:[`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Vcf`](./vcf) . [`Mbox`](./mbox) . [`Pst`](./pst) . [`Ost`](./ost) . E-posta biçimleri hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/email) .

```csharp
public sealed class EmailFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmailFileType](emailfiletype)() | Serileştirme oluşturucu |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dosya türü açıklaması |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Dosya uzantısı |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | family dosyası |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Dosya biçimi |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Geçerli nesneyi diğeriyle karşılaştırır. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Dizi gösterimi |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | EML dosya biçimi, Outlook ve diğer ilgili uygulamalar kullanılarak kaydedilen e-posta mesajlarını temsil eder. Hemen hemen tüm e-posta istemcileri, RFC-822 İnternet İleti Biçimi Standardı ile uyumluluğu nedeniyle bu dosya biçimini destekler. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/email/eml) . |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | EMLX dosya formatı Apple tarafından uygulanır ve geliştirilir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya biçimini kullanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/email/emlx) . |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox dosya formatı, elektronik posta mesajlarının toplanması için bir kapsayıcıyı temsil eden genel bir terimdir. İletiler, ekleriyle birlikte kabın içinde saklanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajlarını, kişileri, randevuları veya diğer görevleri depolamak için kullanılan bir dosya biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/email/msg) . |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST veya Çevrimdışı Depolama Dosyaları, Microsoft Outlook kullanılarak Exchange Server'a kaydolduktan sonra yerel makinede çevrimdışı modda kullanıcının posta kutusu verilerini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/email/ost) . |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | .PST uzantılı dosyalar, çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyalarını (Kişisel Depolama Tablosu olarak da adlandırılır) temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/email/pst) . |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Sanal Kart Formatı) veya vCard, iletişim bilgilerini saklamak için kullanılan bir dijital dosya formatıdır. Biçim, popüler bilgi alışverişi uygulamaları arasında veri alışverişi için yaygın olarak kullanılır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/email/vcf) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
