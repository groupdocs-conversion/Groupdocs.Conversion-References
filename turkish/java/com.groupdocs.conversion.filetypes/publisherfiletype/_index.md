---
title: "PublisherFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Publisher belgelerini tanımlar."
type: docs
weight: 24
url: /tr/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Publisher belgelerini tanımlar.
Aşağıdaki türleri içerir:
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
Yazı tipi biçimleri hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/publisher).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Pub](#Pub) | PUB dosyası, bir Microsoft Publisher belge dosya biçimidir. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Serileştirme yapıcısı


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


PUB dosyası, bir Microsoft Publisher belge dosya biçimidir. Bültenler, broşürler, el ilanları, kartvizitler vb. gibi çeşitli tasarım düzeni belgeleri oluşturmak için kullanılır. PUB dosyaları metin, raster ve vektör görüntüler içerebilir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
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
