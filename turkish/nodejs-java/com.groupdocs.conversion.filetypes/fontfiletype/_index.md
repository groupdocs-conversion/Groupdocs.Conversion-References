---
title: "FontFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Yazı tipi belgelerini tanımlar."
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Font belgelerini tanımlar. Aşağıdaki türleri içerir: [Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Ttf), [Eot](../../com.groupdocs.conversion.filetypes/fontfiletype\#Eot), [Otf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Otf), [Cff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Cff), [Type1](../../com.groupdocs.conversion.filetypes/fontfiletype\#Type1), [Woff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff), [Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff2), Font formatları hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/font
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontFileType()](#FontFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Ttf](#Ttf) | .ttf uzantılı bir dosya, TrueType spesifikasyonlarına dayalı font dosyalarını temsil eder. |
| [Eot](#Eot) | .eot uzantılı bir dosya, bir belgeye gömülü OpenType fontudur. |
| [Otf](#Otf) | .otf uzantılı bir dosya, OpenType font formatına işaret eder. |
| [Cff](#Cff) | .cff uzantılı bir dosya, Compact Font Format (CFF) olup aynı zamanda PostScript Type 1 veya CIDFont olarak da bilinir. |
| [Type1](#Type1) | Type 1 fontları, PostScript kullanabilen masaüstü yayıncılık yazılımları ve yazıcılarda yaygın olarak kullanılan, artık kullanımdan kaldırılmış bir Adobe teknolojisidir. |
| [Woff](#Woff) | .woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web font dosyasıdır. |
| [Woff2](#Woff2) | .woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web font dosyasıdır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Serileştirme yapıcısı

### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


.ttf uzantılı bir dosya, TrueType spesifikasyonlarına dayalı font dosyalarını temsil eder. İlk olarak Apple Computer, Inc tarafından Mac OS için tasarlanıp piyasaya sürülmüş, daha sonra Microsoft tarafından Windows OS için benimsenmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/font/ttf/

### Eot {#Eot}
```
public static final FontFileType Eot
```


.eot uzantılı bir dosya, bir belgeye gömülü OpenType fontudur. Bunlar çoğunlukla bir web sayfası gibi web dosyalarında kullanılır. Microsoft tarafından oluşturulmuş ve PowerPoint sunumu .pps dosyası dahil Microsoft ürünleri tarafından desteklenir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/font/eot/

### Otf {#Otf}
```
public static final FontFileType Otf
```


.otf uzantılı bir dosya, OpenType font formatına işaret eder. OTF font formatı daha ölçeklenebilir olup dijital tipografi için TTF formatlarının mevcut özelliklerini genişletir. Microsoft ve Adobe tarafından geliştirilen OTF, PostScript ve TrueType font formatlarının özelliklerini birleştirir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/font/otf/

### Cff {#Cff}
```
public static final FontFileType Cff
```


.cff uzantılı bir dosya, Compact Font Format (CFF) olup aynı zamanda PostScript Type 1 veya CIDFont olarak da bilinir. CFF, bir FontSet olarak adlandırılan tek bir birimde birden fazla fontu depolayan bir kapsayıcı görevi görür. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/font/cff/

### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type 1 fontları, PostScript kullanabilen masaüstü yayıncılık yazılımları ve yazıcılarda yaygın olarak kullanılan, artık kullanımdan kaldırılmış bir Adobe teknolojisidir. Type 1 fontları birçok modern platformda, web tarayıcısında ve mobil işletim sisteminde desteklenmese de, bazı işletim sistemlerinde hâlâ desteklenmektedir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/font/type1/

### Woff {#Woff}
```
public static final FontFileType Woff
```


.woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web font dosyasıdır. TrueType (.TTF) veya OpenType (.OTT) font tiplerinden birine dayalı format‑özel sıkıştırılmış bir kapsayıcıya sahiptir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/font/woff/

### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


.woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web font dosyasıdır. TrueType (.TTF) veya OpenType (.OTT) font tiplerinden birine dayalı format‑özel sıkıştırılmış bir kapsayıcıya sahiptir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/font/woff/

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
