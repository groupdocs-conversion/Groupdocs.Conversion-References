---
title: AudioFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Ses belgelerini tanımlar Aşağıdaki türleri içerir Mp3./audiofiletype/mp3  Aac./audiofiletype/aac  Aiff./audiofiletype/aiff  Flac./audiofiletype/flac  M4a./audiofiletype/m4a  Wma./audiofiletype/wma  Ac3./audiofiletype/ac3  Ogg./audiofiletype/ogg  Wav./audiofiletype/wav  Ses biçimleri hakkında daha fazla bilgi edininBuradahttps//docs.fileformat.com/audio/ .
type: docs
weight: 850
url: /tr/net/groupdocs.conversion.filetypes/audiofiletype/
---
## AudioFileType class

Ses belgelerini tanımlar Aşağıdaki türleri içerir: [`Mp3`](./mp3) , [`Aac`](./aac) , [`Aiff`](./aiff) , [`Flac`](./flac) , [`M4a`](./m4a) , [`Wma`](./wma) , [`Ac3`](./ac3) , [`Ogg`](./ogg) , [`Wav`](./wav) , Ses biçimleri hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/) .

```csharp
public sealed class AudioFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [AudioFileType](audiofiletype)() | Serileştirme oluşturucu |

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
| static readonly [Aac](../../groupdocs.conversion.filetypes/audiofiletype/aac) | AAC (Gelişmiş Ses Kodlaması), kayıplı ses sıkıştırmasına dayalı ses dosyalarını temsil eden dijital ses kodlama standardını ifade eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/aac/) . |
| static readonly [Ac3](../../groupdocs.conversion.filetypes/audiofiletype/ac3) | .ac3 uzantılı bir dosya, Dolby Laboratories tarafından sunulan bir Audio Codec 3 dosyasıdır. Altı adede kadar ses çıkışı kanalı içerebilen bir ses formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/ac3/) . |
| static readonly [Aiff](../../groupdocs.conversion.filetypes/audiofiletype/aiff) | AIFF (Ses Değişim Dosyası Biçimi), Apple tarafından 1998'de geliştirilen sıkıştırılmamış bir ses dosyası biçimidir, ancak EA IFF 85'i temel alır Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/aiff/) . |
| static readonly [Flac](../../groupdocs.conversion.filetypes/audiofiletype/flac) | FLAC(Free Lossless Audio Codec), Xiph.Org Foundation tarafından geliştirilen kayıpsız bir sıkıştırma ses kodlama formatıdır Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/flac/) . |
| static readonly [M4a](../../groupdocs.conversion.filetypes/audiofiletype/m4a) | M4A dosya biçimi, kayıplı sıkıştırma olarak bilinen AAC (Gelişmiş Ses Kodlaması) kullanılarak oluşturulan bir ses dosyasıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/m4a/) . |
| static readonly [Mp3](../../groupdocs.conversion.filetypes/audiofiletype/mp3) | .mp3 uzantılı dosyalar, resmi olarak MPEG-1 Ses Katmanı III veya MPEG-2 Ses Katmanı III'ü temel alan ses dosyaları için dijital olarak kodlanmış dosya biçimleridir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/mp3/) . |
| static readonly [Ogg](../../groupdocs.conversion.filetypes/audiofiletype/ogg) | OGG, .ogg uzantısıyla kaydedilen bir Ogg Vorbis Sıkıştırılmış Ses Dosyasıdır. OGG dosyaları, ses verilerini depolamak için kullanılır ve sanatçı ve parça bilgileri ile meta verileri de içerebilir. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/ogg/) . |
| static readonly [Wav](../../groupdocs.conversion.filetypes/audiofiletype/wav) | WAVE (Dalga Biçimi Ses Dosyası Biçimi) olarak bilinen WAV, dijital ses dosyalarını depolamak için Microsoft'un Kaynak Değişim Dosyası Biçimi (RIFF) özelliğinin bir alt kümesidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/ogg/) . |
| static readonly [Wma](../../groupdocs.conversion.filetypes/audiofiletype/wma) | .wma uzantılı bir dosya, Gelişmiş Sistem Biçimi (ASF) biçiminde kaydedilen bir ses dosyasını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/audio/wma/) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
