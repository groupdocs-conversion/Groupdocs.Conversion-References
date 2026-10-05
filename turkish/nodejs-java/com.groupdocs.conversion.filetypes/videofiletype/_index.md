---
title: "VideoDosyaTürü"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Video belgelerini tanımlar. Aşağıdaki türleri içerir        Video formatları hakkında daha fazla bilgi edinin."
type: docs
weight: 26
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Video belgelerini tanımlar Aşağıdaki türleri içerir: , , , , , , , Video formatları hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/video/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VideoFileType()](#VideoFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Mp4](#Mp4) | MP4 (MPEG-4 Part 14'ün kısaltması), ISO/IEC 14496-12:2004 temelinde ve QuickTime Dosya Formatına dayanan bir dosya formatıdır ve resmi olarak İlk Nesne Tanımlayıcıları (IOD) ve diğer MPEG özelliklerinin desteğini belirtir. |
| [Avi](#Avi) | AVI dosya formatı, Microsoft tarafından tanıtılan bir Ses Video çoklu ortam kapsayıcı dosya formatıdır. |
| [Flv](#Flv) | FLV (Flash Video), .flv uzantısına sahip bir kapsayıcı dosya formatıdır. |
| [Mkv](#Mkv) | MKV (Matroska Video), MOV ve AVI formatına benzer bir çoklu ortam kapsayıcısıdır ancak aynı dosyada birden fazla ses ve altyazı izini destekler. |
| [Mov](#Mov) | MOV veya QuickTime dosya formatı, Apple tarafından geliştirilen bir çoklu ortam kapsayıcısıdır: bir veya daha fazla iz içerir, her iz belirli bir veri türünü (örneğin) tutar. |
| [Webm](#Webm) | .webm uzantılı bir dosya, açık ve telif ücreti olmayan WebM dosya formatına dayalı bir video dosyasıdır. |
| [Wmv](#Wmv) | Windows Media Video, Microsoft tarafından geliştirilen sıkıştırılmış bir video formatıdır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Serileştirme yapıcısı

### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (MPEG-4 Part 14'ün kısaltması), ISO/IEC 14496-12:2004 temelinde ve QuickTime Dosya Formatına dayanan bir dosya formatıdır ve resmi olarak İlk Nesne Tanımlayıcıları (IOD) ve diğer MPEG özelliklerinin desteğini belirtir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/video/mp4/

### Avi {#Avi}
```
public static final VideoFileType Avi
```


AVI dosya formatı, Microsoft tarafından tanıtılan bir Ses Video çoklu ortam kapsayıcı dosya formatıdır. XVid ve DivX gibi çeşitli codec'ler (Kodlayıcılar/Kod çözücüler) kullanılarak oluşturulan ve sıkıştırılan ses ve video verilerini tutar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/video/avi/

### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video), .flv uzantısına sahip bir kapsayıcı dosya formatıdır. FLV, Adobe Flash Player veya Adobe Air kullanarak internet üzerinden ses/video içeriği sunmak için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/video/flv/

### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video), MOV ve AVI formatına benzer bir çoklu ortam kapsayıcısıdır ancak aynı dosyada birden fazla ses ve altyazı izini destekler. Bir MKV dosyası, video için kullanılan Matroska çoklu ortam kapsayıcı formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/video/mkv/

### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV veya QuickTime dosya formatı, Apple tarafından geliştirilen bir çoklu ortam kapsayıcısıdır: bir veya daha fazla iz içerir, her iz belirli bir veri türünü (örneğin Video, Ses, metin vb.) tutar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/video/mov/

### Webm {#Webm}
```
public static final VideoFileType Webm
```


.webm uzantılı bir dosya, açık ve telif ücreti olmayan WebM dosya formatına dayalı bir video dosyasıdır. Web üzerinde video paylaşımı için tasarlanmıştır ve video ve ses formatlarını içeren dosya kapsayıcı yapısını tanımlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/video/webm//

### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video, Microsoft tarafından geliştirilen sıkıştırılmış bir video formatıdır. Motion Picture and Television Engineers (SMPTE) Derneği tarafından standartlaştırıldıktan sonra, WMV artık açık bir standart format olarak kabul edilmektedir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/video/wmv/

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
