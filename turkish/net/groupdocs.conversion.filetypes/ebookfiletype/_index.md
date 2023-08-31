---
title: EBookFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: EKitap belgelerini tanımlar. Aşağıdaki dosya türlerini içerir Epub./ebookfiletype/epubMobi./ebookfiletype/mobiAzw3./ebookfiletype/azw3
type: docs
weight: 910
url: /tr/net/groupdocs.conversion.filetypes/ebookfiletype/
---
## EBookFileType class

E-Kitap belgelerini tanımlar. Aşağıdaki dosya türlerini içerir: [`Epub`](./epub)[`Mobi`](./mobi)[`Azw3`](./azw3)

```csharp
public sealed class EBookFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EBookFileType](ebookfiletype)() | Serileştirme oluşturucu |

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
| static readonly [Azw3](../../groupdocs.conversion.filetypes/ebookfiletype/azw3) | Kindle Format 8 (KF8) olarak da bilinen AZW3, Amazon Kindle cihazları için geliştirilmiş AZW ebook dijital dosya formatının değiştirilmiş versiyonudur. Biçim, eski AZW dosyalarına yönelik bir geliştirmedir ve Kindle Fire cihazlarında yalnızca ata dosya biçimi, yani MOBI ve AZW için geriye dönük uyumlulukla kullanılır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Epub](../../groupdocs.conversion.filetypes/ebookfiletype/epub) | EPUB uzantısı, yayıncılar ve tüketiciler için standart bir dijital yayın biçimi sağlayan bir e-kitap dosyası biçimidir. Format şimdiye kadar o kadar yaygın hale geldi ki birçok e-okuyucu ve yazılım uygulaması tarafından destekleniyor. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/ebook/epub) . |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/ebookfiletype/mobi) | MOBI dosya formatı, en yaygın kullanılan e-kitap dosya formatlarından biridir. Biçim, eski OEB (Açık E-Kitap Biçimi) biçiminin geliştirilmiş halidir ve Mobipocket Reader için tescilli biçim olarak kullanılmıştır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/ebook/mobi) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->