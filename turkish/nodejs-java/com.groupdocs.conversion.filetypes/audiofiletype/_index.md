---
title: "AudioFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Ses belgelerini tanımlar. Aşağıdaki türleri içerir          Ses formatları hakkında daha fazla bilgi edinin burada."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

Ses belgelerini tanımlar. Aşağıdaki türleri içerir: , , , , , , , , , Ses formatları hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AudioFileType()](#AudioFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Mp3](#Mp3) | .mp3 uzantılı dosyalar, resmi olarak MPEG-1 Audio Layer III veya MPEG-2 Audio Layer III tabanlı olan dijital olarak kodlanmış ses dosyası formatlarıdır. |
| [Aac](#Aac) | AAC (Advanced Audio Coding), kayıplı ses sıkıştırması tabanlı ses dosyalarını temsil eden dijital ses kodlama standardını ifade eder. |
|  | [Aiff](#Aiff) | AIFF (Audio Interchange File Format), 1998'de Apple tarafından geliştirilen sıkıştırılmamış bir ses dosyası formatıdır, ancak EA IFF 85 temellidir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][]. |


[here]: https://docs.fileformat.com/audio/aiff/ |
|  | [Flac](#Flac) | FLAC (Free Lossless Audio Codec), Xiph.Org Foundation tarafından geliştirilen kayıpsız sıkıştırma ses kodlama formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][]. |


[here]: https://docs.fileformat.com/audio/flac/ |
| [M4a](#M4a) | M4A dosya formatı, kayıplı sıkıştırma olarak bilinen AAC (Advanced Audio Coding) kullanılarak oluşturulan bir ses dosyasıdır. |
| [Wma](#Wma) | .wma uzantılı bir dosya, Advanced Systems Format (ASF) formatında kaydedilmiş bir ses dosyasını temsil eder. |
| [Ac3](#Ac3) | .ac3 uzantılı bir dosya, Dolby Laboratories tarafından tanıtılan bir Audio Codec 3 dosasıdır. |
| [Ogg](#Ogg) | OGG, .ogg uzantısıyla kaydedilen bir Ogg Vorbis Sıkıştırılmış Ses Dosyasıdır. |
| [Wav](#Wav) | WAV, WAVE (Waveform Audio File Format) olarak bilinir, dijital ses dosyalarını depolamak için Microsoft’un Resource Interchange File Format (RIFF) spesifikasyonunun bir alt kümesidir. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


Serileştirme yapıcısı

### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


.mp3 uzantılı dosyalar, resmi olarak MPEG-1 Audio Layer III veya MPEG-2 Audio Layer III tabanlı olan dijital olarak kodlanmış ses dosyası formatlarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/mp3/

### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding), kayıplı ses sıkıştırması tabanlı ses dosyalarını temsil eden dijital ses kodlama standardını ifade eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/aac/

### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


AIFF (Audio Interchange File Format), 1998'de Apple tarafından geliştirilen sıkıştırılmamış bir ses dosyası formatıdır, ancak EA IFF 85 temellidir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/aiff/

### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC (Free Lossless Audio Codec), Xiph.Org Foundation tarafından geliştirilen kayıpsız sıkıştırma ses kodlama formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/flac/

### M4a {#M4a}
```
public static final AudioFileType M4a
```


M4A dosya formatı, kayıplı sıkıştırma olarak bilinen AAC (Advanced Audio Coding) kullanılarak oluşturulan bir ses dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/m4a/

### Wma {#Wma}
```
public static final AudioFileType Wma
```


.wma uzantılı bir dosya, Advanced Systems Format (ASF) formatında kaydedilmiş bir ses dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/wma/

### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


.ac3 uzantılı bir dosya, Dolby Laboratories tarafından tanıtılan bir Audio Codec 3 dosasıdır. Bu, en fazla altı kanal ses çıkışı içerebilen bir ses formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/ac3/

### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG, .ogg uzantısıyla kaydedilen bir Ogg Vorbis Sıkıştırılmış Ses Dosyasıdır. OGG dosyaları ses verilerini depolamak için kullanılır ve sanatçı, parça bilgisi ve meta verileri de içerebilir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/ogg/

### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, WAVE (Waveform Audio File Format) olarak bilinir, dijital ses dosyalarını depolamak için Microsoft’un Resource Interchange File Format (RIFF) spesifikasyonunun bir alt kümesidir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/audio/ogg/

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
