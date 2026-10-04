---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Word Processing dosyalarını tanımlar; bu dosyalar kullanıcı bilgilerini düz metin veya zengin metin formatında içerir. Düz metin dosya formatı biçimlendirilmemiş metin içerir ve font ya da sayfa ayarları gibi özellikler uygulanamaz. Buna karşılık, zengin metin dosya formatı, font tipi, stil, kalın, italik, altı çizili vb. ayarlama, sayfa kenar boşlukları, başlıklar, madde işaretleri ve numaralar ve çeşitli diğer biçimlendirme özellikleri gibi seçeneklere izin verir. Aşağıdaki dosya türlerini içerir Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt Md./wordprocessingfiletype/md. Word Processing formatları hakkında daha fazla bilgi için https//wiki.fileformat.com/wordprocessing adresine bakabilirsiniz."
type: docs
weight: 1280
url: /tr/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Düz metin veya zengin metin biçiminde kullanıcı bilgileri içeren Word İşleme dosyalarını tanımlar. Düz metin dosya biçimi biçimlendirilmemiş metin ve yazı tipi veya sayfa ayarları gibi hiçbir şey içermez ve uygulanamaz. Buna karşılık, zengin metin dosya biçimi yazı tipi ayarları, stiller (kalın, italik, altı çizili vb.), sayfa kenar boşlukları, başlıklar, madde işaretleri ve numaralar gibi biçimlendirme seçeneklerine ve çeşitli diğer biçimlendirme özelliklerine izin verir. Aşağıdaki dosya türlerini içerir: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Word İşleme biçimleri hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Serileştirme yapıcısı |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | .doc uzantılı dosyalar, Microsoft Word veya diğer kelime işlem programları tarafından ikili dosya biçiminde oluşturulan belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümleri tarafından oluşturulan belgelerdir. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX, Microsoft Word belgeleri için yaygın bir biçimdir. Microsoft Office 2007'nin yayınlanmasıyla 2007'den itibaren tanıtılan bu yeni Belge biçiminin yapısı, düz ikili formatından XML ve ikili dosyaların bir kombinasyonuna değiştirildi. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | .DOT uzantılı dosyalar, daha sonraki DOC veya DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip şablon dosyalarıdır ve Microsoft Word tarafından oluşturulur. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | DOTM uzantılı bir dosya, Microsoft Word 2007 veya daha yeni sürümleriyle oluşturulan şablon dosyasını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | .DOTX uzantılı dosyalar, daha sonraki DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip şablon dosyalarıdır ve Microsoft Word tarafından oluşturulur. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word, ZIP paketi yerine düz bir XML dosyasında depolanan Office Open XML WordprocessingML'dir. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Markdown dil varyantlarıyla oluşturulan metin dosyaları .MD veya .MARKDOWN dosya uzantısıyla kaydedilir. MD dosyaları, girintiler, tablo biçimlendirme, yazı tipleri ve başlıklar gibi metnin nasıl biçimlendirileceğini tanımlayan satır içi metin sembolleri içeren Markdown dilini kullanan düz metin formatında kaydedilir. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT dosyaları, OpenDocument Metin Dosyası biçemine dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | .OTT uzantılı dosyalar, OASIS'in OpenDocument standart biçimine uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Microsoft tarafından tanıtılan ve belgelenen Rich Text Format (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | .TXT uzantılı bir dosya, satır biçiminde düz metin içeren bir metin belgesini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/txt). |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
