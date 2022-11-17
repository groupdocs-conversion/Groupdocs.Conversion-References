---
title: WordProcessingFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Düz metin veya zengin metin biçiminde kullanıcı bilgilerini içeren Kelime İşleme dosyalarını tanımlar. Düz metin dosyası biçimi biçimlendirilmemiş metin içerir ve hiçbir yazı tipi veya sayfa ayarı vb. uygulanamaz. Aksine zengin bir metin dosyası formatı yazı tipi tipini stilleri kalın italik altı çizili vb. sayfa kenar boşluklarını başlıkları madde işaretlerini ve sayıları ve diğer birçok biçimlendirme özelliğini ayarlama gibi biçimlendirme seçeneklerine izin verir. Aşağıdaki dosya türlerini içerir Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi./wordprocessingfiletype/mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log./wordprocessingfiletype/log . Kelime İşleme biçimleri hakkında daha fazla bilgi edininburadahttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 960
url: /tr/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Düz metin veya zengin metin biçiminde kullanıcı bilgilerini içeren Kelime İşleme dosyalarını tanımlar. Düz metin dosyası biçimi, biçimlendirilmemiş metin içerir ve hiçbir yazı tipi veya sayfa ayarı vb. uygulanamaz. Aksine, zengin bir metin dosyası formatı, yazı tipi tipini, stilleri (kalın, italik, altı çizili vb.), sayfa kenar boşluklarını, başlıkları, madde işaretlerini ve sayıları ve diğer birçok biçimlendirme özelliğini ayarlama gibi biçimlendirme seçeneklerine izin verir. Aşağıdaki dosya türlerini içerir: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`Mobi`](./mobi) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . [`Log`](./log) . Kelime İşleme biçimleri hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Serileştirme yapıcısı |

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
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Dizi gösterimi |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Azw3](../../groupdocs.conversion.filetypes/wordprocessingfiletype/azw3) | Kindle Format 8 (KF8) olarak da bilinen AZW3, Amazon Kindle cihazları için geliştirilmiş AZW ebook dijital dosya formatının değiştirilmiş versiyonudur. Biçim, eski AZW dosyalarına yönelik bir geliştirmedir ve Kindle Fire cihazlarında yalnızca ata dosya biçimi, yani MOBI ve AZW için geriye dönük uyumlulukla kullanılır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | .doc uzantılı dosyalar, Microsoft Word tarafından oluşturulan belgeleri veya ikili dosya biçimindeki diğer kelime işlem belgelerini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM dosyaları, Microsoft Word 2007 veya daha yüksek sürümde oluşturulmuş ve makro çalıştırma özelliğine sahip belgelerdir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX, Microsoft Word belgeleri için iyi bilinen bir biçimdir. 2007'den itibaren Microsoft Office 2007'nin piyasaya sürülmesiyle tanıtılan bu yeni Belge biçiminin yapısı, düz ikiliden XML ve ikili dosyaların birleşimine değiştirildi. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | .DOT uzantılı dosyalar, daha fazla DOC veya DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | DOTM uzantılı bir dosya, Microsoft Word 2007 veya üstü ile oluşturulan şablon dosyasını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | DOTX uzantılı dosyalar, başka DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalardır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Log](../../groupdocs.conversion.filetypes/wordprocessingfiletype/log) | .LOG uzantılı bir dosya, satır biçiminde düz metin içeren bir metin belgesini temsil eder. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Markdown dil lehçeleriyle oluşturulan metin dosyaları, .MD veya .MARKDOWN dosya uzantısıyla kaydedilir. MD dosyaları, girintiler, tablo biçimlendirme, yazı tipleri ve başlıklar gibi bir metnin nasıl biçimlendirilebileceğini tanımlayan satır içi metin sembollerini de içeren Markdown dilini kullanan düz metin biçiminde kaydedilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/wordprocessingfiletype/mobi) | MOBI dosya formatı, en yaygın kullanılan e-kitap dosya formatlarından biridir. Biçim, eski OEB (Açık E-Kitap Biçimi) biçiminin geliştirilmiş halidir ve Mobipocket Reader için tescilli biçim olarak kullanılmıştır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/ebook/mobi) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT dosyaları, OpenDocument Metin Dosyası formatına dayalı kelime işlemci uygulamaları ile oluşturulan belge türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | OTT uzantılı dosyalar, OASIS'in OpenDocument standart biçimine uygun uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Microsoft tarafından tanıtılan ve belgelenen Zengin Metin Biçimi (RTF), uygulamalarda kullanım için biçimlendirilmiş metin ve grafikleri kodlama yöntemini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Sql](../../groupdocs.conversion.filetypes/wordprocessingfiletype/sql) | .SQL uzantılı bir dosya, sql içeren bir metin belgesini temsil eder. |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | .TXT uzantılı bir dosya, satır biçiminde düz metin içeren bir metin belgesini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/txt) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
