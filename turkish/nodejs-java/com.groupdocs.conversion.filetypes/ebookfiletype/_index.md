---
title: "EBookFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "3D grafik dosya formatları için kullanılan ve 2D veya 3D tasarımlar içerebilen CAD (Computer Aided Design) belgelerini tanımlar."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

CAD belgelerini (Computer Aided Design) tanımlar; bu belgeler 3D grafik dosya formatları için kullanılır ve 2D veya 3D tasarımlar içerebilir. Aşağıdaki türleri içerir: [Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Epub), [Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Mobi), [Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Azw3), CAD formatları hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EBookFileType()](#EBookFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Epub](#Epub) | EPUB uzantısı, yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlayan bir e-kitap dosya formatıdır. |
| [Mobi](#Mobi) | MOBI dosya formatı, en yaygın kullanılan e-kitap dosya formatlarından biridir. |
| [Azw3](#Azw3) | AZW3, Kindle Format 8 (KF8) olarak da bilinir, Amazon Kindle cihazları için geliştirilen AZW e-kitap dijital dosya formatının değiştirilmiş sürümüdür. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Serileştirme yapıcısı

### Epub {#Epub}
```
public static final EBookFileType Epub
```


EPUB uzantısı, yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlayan bir e-kitap dosya formatıdır. Bu format artık o kadar yaygın ki birçok e-okuyucu ve yazılım uygulaması tarafından desteklenmektedir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


MOBI dosya formatı, en yaygın kullanılan e-kitap dosya formatlarından biridir. Bu format, eski OEB (Open Ebook Format) formatının bir geliştirmesidir ve Mobipocket Reader için özel bir format olarak kullanılmıştır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, Kindle Format 8 (KF8) olarak da bilinir, Amazon Kindle cihazları için geliştirilen AZW e-kitap dijital dosya formatının değiştirilmiş sürümüdür. Bu format, eski AZW dosyalarının bir geliştirmesidir ve yalnızca Kindle Fire cihazlarında, önceki dosya formatı olan MOBI ve AZW ile geriye dönük uyumluluk sağlayarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/ebook/azw3/

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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
