---
title: WordProcessingFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Düz metin veya zengin metin biçiminde kullanıcı bilgilerini içeren Kelime İşleme dosyalarını tanımlar. Düz metin dosyası biçimi biçimlendirilmemiş metin içerir ve hiçbir yazı tipi veya sayfa ayarı vb. uygulanamaz. Aksine zengin bir metin dosyası formatı yazı tipi tipini stilleri kalın italik altı çizili vb. sayfa kenar boşluklarını başlıkları madde işaretlerini ve sayıları ve diğer birçok biçimlendirme özelliğini ayarlama gibi biçimlendirme seçeneklerine izin verir. Aşağıdaki dosya türlerini içerir Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log . Kelime İşleme biçimleri hakkında daha fazla bilgi edininBuradahttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 1090
url: /tr/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Düz metin veya zengin metin biçiminde kullanıcı bilgilerini içeren Kelime İşleme dosyalarını tanımlar. Düz metin dosyası biçimi, biçimlendirilmemiş metin içerir ve hiçbir yazı tipi veya sayfa ayarı vb. uygulanamaz. Aksine, zengin bir metin dosyası formatı, yazı tipi tipini, stilleri (kalın, italik, altı çizili vb.), sayfa kenar boşluklarını, başlıkları, madde işaretlerini ve sayıları ve diğer birçok biçimlendirme özelliğini ayarlama gibi biçimlendirme seçeneklerine izin verir. Aşağıdaki dosya türlerini içerir: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , Mobi , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . Log . Kelime İşleme biçimleri hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Serileştirme oluşturucu |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | .doc uzantılı dosyalar, Microsoft Word tarafından oluşturulan belgeleri veya ikili dosya biçimindeki diğer kelime işlem belgelerini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM dosyaları, Microsoft Word 2007 veya daha yüksek sürümde oluşturulmuş ve makro çalıştırma özelliğine sahip belgelerdir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX, Microsoft Word belgeleri için iyi bilinen bir biçimdir. 2007'den itibaren Microsoft Office 2007'nin piyasaya sürülmesiyle tanıtılan bu yeni Belge biçiminin yapısı, düz ikiliden XML ve ikili dosyaların birleşimine değiştirildi. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | .DOT uzantılı dosyalar, daha fazla DOC veya DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | DOTM uzantılı bir dosya, Microsoft Word 2007 veya üstü ile oluşturulan şablon dosyasını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | DOTX uzantılı dosyalar, daha fazla DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Markdown dil lehçeleriyle oluşturulan metin dosyaları, .MD veya .MARKDOWN dosya uzantısıyla kaydedilir. MD dosyaları, girintiler, tablo biçimlendirme, yazı tipleri ve başlıklar gibi bir metnin nasıl biçimlendirilebileceğini tanımlayan satır içi metin sembollerini de içeren Markdown dilini kullanan düz metin biçiminde kaydedilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT dosyaları, OpenDocument Metin Dosyası biçimini temel alan kelime işlem uygulamalarıyla oluşturulan belge türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | OTT uzantılı dosyalar, uygulamalar tarafından OASIS'in OpenDocument standart formatına uygun olarak oluşturulan şablon belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Microsoft tarafından tanıtılan ve belgelenen Zengin Metin Biçimi (RTF), uygulamalarda kullanılmak üzere biçimlendirilmiş metin ve grafikleri kodlama yöntemini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | .TXT uzantılı bir dosya, satır biçiminde düz metin içeren bir metin belgesini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/txt) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
