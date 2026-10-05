---
title: "WordProcessingFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Kullanıcı bilgilerini düz metin veya zengin metin biçiminde içeren Kelime İşleme dosyalarını tanımlar."
type: docs
weight: 28
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Word Processing dosyalarını, kullanıcı bilgilerini düz metin veya zengin metin formatında içeren dosyalar olarak tanımlar. Düz metin dosya formatı biçimlendirilmemiş metin içerir ve font ya da sayfa ayarları gibi şeyler uygulanamaz. Buna karşılık, zengin metin dosya formatı font tipi ayarlama, stiller (kalın, italik, altı çizili vb.), sayfa kenar boşlukları, başlıklar, madde işaretleri ve numaralar gibi biçimlendirme seçeneklerine izin verir ve çeşitli diğer biçimlendirme özelliklerini destekler. Aşağıdaki dosya türlerini içerir: [Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Doc), [Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docm), [Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docx), [Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dot), [Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotm), [Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotx), [Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Odt), [Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Ott), [Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Rtf), [Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Txt), [Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Md), Word Processing formatları hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingFileType()](#WordProcessingFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Doc](#Doc) | .doc uzantılı dosyalar, Microsoft Word veya diğer kelime işlem programları tarafından ikili dosya formatında oluşturulan belgeleri temsil eder. |
| [Docm](#Docm) | DOCM dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümleriyle oluşturulan belgelerdir. |
| [Docx](#Docx) | DOCX, Microsoft Word belgeleri için iyi bilinen bir formattır. |
| [Dot](#Dot) | .DOT uzantılı dosyalar, daha sonraki DOC veya DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalardır. |
| [Dotm](#Dotm) | DOTM uzantılı bir dosya, Microsoft Word 2007 veya daha yeni sürümleriyle oluşturulan şablon dosyayı temsil eder. |
| [Dotx](#Dotx) | .DOTX uzantılı dosyalar, daha sonraki DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalardır. |
| [Rtf](#Rtf) | Microsoft tarafından tanıtılan ve belgelenen Rich Text Format (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder. |
| [Odt](#Odt) | ODT dosyaları, OpenDocument Text dosya formatına dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir. |
| [Ott](#Ott) | OTT uzantılı dosyalar, OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. |
| [Txt](#Txt) | .TXT uzantılı bir dosya, satır şeklinde düz metin içeren bir metin belgesini temsil eder. |
| [Md](#Md) | Markdown dil varyantlarıyla oluşturulan metin dosyaları .MD veya .MARKDOWN dosya uzantısıyla kaydedilir. |
| [Ml](#Ml) | Ml dosyası |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


Serileştirme yapıcısı

### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


.doc uzantılı dosyalar, Microsoft Word veya diğer kelime işlem programları tarafından ikili dosya formatında oluşturulan belgeleri temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


DOCM dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümleriyle oluşturulan belgelerdir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX, Microsoft Word belgeleri için iyi bilinen bir formattır. Microsoft Office 2007'nin yayınlanmasıyla 2007'den itibaren tanıtılan bu yeni Belge formatının yapısı, düz ikilikten XML ve ikilik dosyaların bir kombinasyonuna değiştirildi. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/docx

### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


Dosyalar .DOT uzantılıdır ve Microsoft Word tarafından, daha fazla DOC veya DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip şablon dosyaları olarak oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/dot

### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


DOTM uzantılı bir dosya, Microsoft Word 2007 veya daha yeni bir sürümle oluşturulmuş şablon dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


Dosyalar .DOTX uzantılıdır ve Microsoft Word tarafından, daha fazla DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip şablon dosyaları olarak oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Microsoft tarafından tanıtılan ve belgelenen Zengin Metin Biçimi (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ODT dosyaları, OpenDocument Metin Dosyası formatına dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/odt

### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


OTT uzantılı dosyalar, OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/ott

### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


.TXT uzantılı bir dosya, satırlar halinde düz metin içeren bir metin belgesini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/txt

### Md {#Md}
```
public static final WordProcessingFileType Md
```


Markdown dil varyantlarıyla oluşturulan metin dosyaları .MD veya .MARKDOWN dosya uzantısıyla kaydedilir. MD dosyaları, satır girintileri, tablo biçimlendirme, yazı tipleri ve başlıklar gibi metnin nasıl biçimlendirileceğini tanımlayan satır içi metin sembolleri içeren Markdown dilini kullanan düz metin formatında kaydedilir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/word-processing/md

### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Ml dosyası

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
```


Dosya türü için varsayılan dönüştürme seçenekleri hazırlandı

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
