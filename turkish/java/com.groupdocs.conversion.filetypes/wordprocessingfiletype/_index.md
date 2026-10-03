---
title: "WordProcessingFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Kullanıcı bilgilerini düz metin veya zengin metin biçiminde içeren Kelime İşleme dosyalarını tanımlar."
type: docs
weight: 28
url: /tr/java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Düz metin veya zengin metin biçiminde kullanıcı bilgileri içeren Kelime İşleme dosyalarını tanımlar. Düz metin dosya biçimi biçimlendirilmemiş metin içerir ve yazı tipi veya sayfa ayarları gibi hiçbir şey uygulanamaz. Buna karşılık, zengin metin dosya biçimi yazı tipi türü ayarlama, stiller (kalın, italik, altı çizili vb.), sayfa kenar boşlukları, başlıklar, madde işaretleri ve numaralar gibi biçimlendirme seçeneklerine izin verir ve çeşitli diğer biçimlendirme özelliklerini sunar.
Aşağıdaki dosya türlerini içerir:
[Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Doc),
[Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docm),
[Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docx),
[Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dot),
[Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotm),
[Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotx),
[Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Odt),
[Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Ott),
[Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Rtf),
[Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Txt),
[Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Md),
Kelime İşleme biçimleri hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing).


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingFileType()](#WordProcessingFileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Doc](#Doc) | Dosya uzantısı .doc olan dosyalar, Microsoft Word veya diğer kelime işlem programları tarafından ikili dosya biçiminde oluşturulan belgeleri temsil eder. |
|
|  | [Docm](#Docm) | DOCM dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümleri tarafından oluşturulan belgelerdir. |
|
|  | [Docx](#Docx) | DOCX, Microsoft Word belgeleri için iyi bilinen bir biçimdir. |
|
|  | [Dot](#Dot) | Dosya uzantısı .DOT olan dosyalar, Microsoft Word tarafından daha fazla DOC veya DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip şablon dosyaları olarak oluşturulur. |
|
|  | [Dotm](#Dotm) | DOTM uzantılı bir dosya, Microsoft Word 2007 veya daha yeni sürümleriyle oluşturulmuş şablon dosyasını temsil eder. |
|
|  | [Dotx](#Dotx) | DOTX uzantılı dosyalar, Microsoft Word tarafından daha fazla DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip şablon dosyaları olarak oluşturulur. |
|
|  | [Rtf](#Rtf) | Microsoft tarafından tanıtılan ve belgelenen Zengin Metin Biçimi (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder. |
|
|  | [Odt](#Odt) | ODT dosyaları, OpenDocument Metin Dosyası biçimine dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir. |
|
|  | [Ott](#Ott) | OTT uzantılı dosyalar, OASIS'in OpenDocument standart biçimine uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. |
|
|  | [Txt](#Txt) | TXT uzantılı bir dosya, satırlar halinde düz metin içeren bir metin belgesini temsil eder. |
|
|  | [Md](#Md) | Markdown dil varyantlarıyla oluşturulan metin dosyaları .MD veya .MARKDOWN dosya uzantısıyla kaydedilir. |
|
|  | [Ml](#Ml) | Ml dosyası |
|
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


Dosya uzantısı .doc olan dosyalar, Microsoft Word veya diğer kelime işlem programları tarafından ikili dosya biçiminde oluşturulan belgeleri temsil eder.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/doc).


### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


DOCM dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümleri tarafından oluşturulan belgelerdir.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/docm).


### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX, Microsoft Word belgeleri için iyi bilinen bir biçimdir. 2007 yılında Microsoft Office 2007'nin yayınlanmasıyla tanıtılan bu yeni Belge biçiminin yapısı, düz ikili formatından XML ve ikili dosyaların bir kombinasyonuna değiştirilmiştir.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/docx).


### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


Dosya uzantısı .DOT olan dosyalar, Microsoft Word tarafından daha fazla DOC veya DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip şablon dosyaları olarak oluşturulur.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/dot).


### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


DOTM uzantılı bir dosya, Microsoft Word 2007 veya daha yeni sürümleriyle oluşturulmuş şablon dosyasını temsil eder.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/dotm).


### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


DOTX uzantılı dosyalar, Microsoft Word tarafından daha fazla DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip şablon dosyaları olarak oluşturulur.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/dotx).


### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Microsoft tarafından tanıtılan ve belgelenen Zengin Metin Biçimi (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/rtf).


### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ODT dosyaları, OpenDocument Metin Dosyası biçimine dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/odt).


### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


OTT uzantılı dosyalar, OASIS'in OpenDocument standart biçimine uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/ott).


### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


TXT uzantılı bir dosya, satırlar halinde düz metin içeren bir metin belgesini temsil eder.
Bu dosya biçimi hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/word-processing/txt).


### Md {#Md}
```
public static final WordProcessingFileType Md
```


Markdown dil dialektleriyle oluşturulan metin dosyaları .MD veya .MARKDOWN dosya uzantısıyla kaydedilir. MD dosyaları, Markdown dilini kullanan düz metin formatında kaydedilir ve bu dil aynı zamanda satır içi metin sembolleri, girintileme, tablo biçimlendirme, yazı tipleri ve başlıklar gibi metnin nasıl biçimlendirileceğini tanımlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/md).


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
