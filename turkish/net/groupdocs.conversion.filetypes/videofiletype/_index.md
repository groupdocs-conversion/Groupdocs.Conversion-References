---
title: "VideoDosyaTürü"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Video belgelerini tanımlar. Aşağıdaki türleri içerir: Mp4./videofiletype/mp4 Avi./videofiletype/avi Flv./videofiletype/flv Mkv./videofiletype/mkv Mov./videofiletype/mov Webm./videofiletype/webm Wmv./videofiletype/wmv. Video formatları hakkında daha fazla bilgi edinin burada https//docs.fileformat.com/video/."
type: docs
weight: 1260
url: /tr/net/groupdocs.conversion.filetypes/videofiletype/
---
## VideoFileType class

Video belgelerini tanımlar. Aşağıdaki türleri içerir: [`Mp4`](./mp4), [`Avi`](./avi), [`Flv`](./flv), [`Mkv`](./mkv), [`Mov`](./mov), [`Webm`](./webm), [`Wmv`](./wmv). Video formatları hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/video/).

```csharp
public sealed class VideoFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [VideoFileType](videofiletype)() | Serileştirme yapıcısı |

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
| static readonly [Avi](../../groupdocs.conversion.filetypes/videofiletype/avi) | AVI dosya formatı, Microsoft tarafından tanıtılan bir Ses Video çoklu ortam konteyner dosya formatıdır. XVid ve DivX gibi çeşitli codec'ler (Kodlayıcılar/Kod çözücüler) kullanılarak oluşturulan ve sıkıştırılan ses ve video verilerini tutar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/video/avi/). |
| static readonly [Flv](../../groupdocs.conversion.filetypes/videofiletype/flv) | FLV (Flash Video), .flv uzantılı bir konteyner dosya formatıdır. FLV, Adobe Flash Player veya Adobe Air kullanarak internet üzerinden ses/video içeriği sunmak için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinmek için [burada](https://docs.fileformat.com/video/flv/). |
| static readonly [Mkv](../../groupdocs.conversion.filetypes/videofiletype/mkv) | MKV (Matroska Video), MOV ve AVI formatına benzer bir multimedya konteyneridir ancak aynı dosyada birden fazla ses ve altyazı izini destekler. Bir MKV dosyası, video için kullanılan Matroska multimedya konteyner formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinmek için [burada](https://docs.fileformat.com/video/mkv/). |
| static readonly [Mov](../../groupdocs.conversion.filetypes/videofiletype/mov) | MOV veya QuickTime dosya formatı, Apple tarafından geliştirilen bir multimedya konteyneridir: bir veya daha fazla iz içerir, her iz belirli bir veri türünü (ör. Video, Ses, metin vb.) tutar. Bu dosya formatı hakkında daha fazla bilgi edinmek için [burada](https://docs.fileformat.com/video/mov/). |
| static readonly [Mp4](../../groupdocs.conversion.filetypes/videofiletype/mp4) | MP4 (MPEG-4 Part 14 kısaltması), ISO/IEC 14496-12:2004 temelli ve QuickTime File Format üzerine kurulu bir dosya formatıdır, ancak İlk Nesne Tanımlayıcıları (IOD) ve diğer MPEG özelliklerini resmi olarak destekler. Bu dosya formatı hakkında daha fazla bilgi edinmek için [burada](https://docs.fileformat.com/video/mp4/). |
| static readonly [Webm](../../groupdocs.conversion.filetypes/videofiletype/webm) | .webm uzantılı bir dosya, açık ve telif ücreti gerektirmeyen WebM dosya formatına dayalı bir video dosyasıdır. Web üzerindeki video paylaşımı için tasarlanmıştır ve video ile ses formatlarını içeren dosya konteyner yapısını tanımlar. Bu dosya formatı hakkında daha fazla bilgi edinmek için [burada](https://docs.fileformat.com/video/webm//). |
| static readonly [Wmv](../../groupdocs.conversion.filetypes/videofiletype/wmv) | Windows Media Video, Microsoft tarafından geliştirilen sıkıştırılmış bir video formatıdır. Society of Motion Picture and Television Engineers (SMPTE) tarafından standartlaştırıldıktan sonra WMV artık açık bir standart format olarak kabul edilmektedir. Bu dosya formatı hakkında daha fazla bilgi edinmek için [burada](https://docs.fileformat.com/video/wmv/). |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
