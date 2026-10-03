---
title: "FontFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Yazı tipi belgelerini tanımlar."
type: docs
weight: 17
url: /tr/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Yazı tipi belgelerini tanımlar.
Aşağıdaki türleri içerir:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
Yazı tipi formatları hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/font).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Ttf](#Ttf) | .ttf uzantılı bir dosya, TrueType spesifikasyonlarına dayalı yazı tipi teknolojisini temsil eder. |
|
|  | [Eot](#Eot) | .eot uzantılı bir dosya, bir belgeye gömülü OpenType yazı tipidir. |
|
|  | [Otf](#Otf) | .otf uzantılı bir dosya, OpenType yazı tipi formatını ifade eder. |
|
|  | [Cff](#Cff) | .cff uzantılı bir dosya, Compact Font Format'tır ve aynı zamanda PostScript Type 1 veya CIDFont olarak da bilinir. |
|
|  | [Type1](#Type1) | Type 1 yazı tipleri, PostScript kullanabilen masaüstü yayıncılık yazılımları ve yazıcılarda yaygın olarak kullanılan, artık kullanılmayan bir Adobe teknolojisidir. |
|
|  | [Woff](#Woff) | .woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web yazı tipi dosyasıdır. |
|
|  | [Woff2](#Woff2) | .woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web yazı tipi dosyasıdır. |
|
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


.ttf uzantılı bir dosya, TrueType spesifikasyonlarına dayalı yazı tipi dosyalarını temsil eder. İlk olarak Apple Computer, Inc tarafından Mac OS için tasarlanıp piyasaya sürülmüş, daha sonra Microsoft tarafından Windows OS için benimsenmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


.eot uzantılı bir dosya, bir belgeye gömülü OpenType yazı tipidir. Bunlar çoğunlukla bir Web sayfası gibi web dosyalarında kullanılır. Microsoft tarafından oluşturulmuş ve PowerPoint sunumu .pps dosyası dahil Microsoft ürünleri tarafından desteklenir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


.otf uzantılı bir dosya, OpenType yazı tipi formatını ifade eder. OTF yazı tipi formatı daha ölçeklenebilir olup, dijital tipografi için TTF formatlarının mevcut özelliklerini genişletir. Microsoft ve Adobe tarafından geliştirilen OTF, PostScript ve TrueType yazı tipi formatlarının özelliklerini birleştirir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


.cff uzantılı bir dosya, Compact Font Format'tır ve aynı zamanda PostScript Type 1 veya CIDFont olarak da bilinir. CFF, bir FontSet olarak bilinen tek bir birimde birden fazla yazı tipini depolayan bir kapsayıcı görevi görür. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type 1 yazı tipleri, PostScript kullanabilen masaüstü yayıncılık yazılımları ve yazıcılarda yaygın olarak kullanılan, artık kullanılmayan bir Adobe teknolojisidir. Type 1 yazı tipleri birçok modern platformda, web tarayıcılarında ve mobil işletim sistemlerinde desteklenmese de, bazı işletim sistemlerinde hâlâ desteklenmektedir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


.woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web yazı tipi dosyasıdır. TrueType (.TTF) veya OpenType (.OTT) yazı tipi türlerinden birine dayalı format‑özel sıkıştırılmış bir kapsayıcıya sahiptir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


.woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web yazı tipi dosyasıdır. TrueType (.TTF) veya OpenType (.OTT) yazı tipi türlerinden birine dayalı format‑özel sıkıştırılmış bir kapsayıcıya sahiptir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/font/woff/).


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
