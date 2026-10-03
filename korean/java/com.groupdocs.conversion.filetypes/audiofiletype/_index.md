---
title: "AudioFileType"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "오디오 문서를 정의합니다. 다음 유형을 포함합니다. 오디오 형식에 대해 자세히 알아보려면 여기에서 확인하세요."
type: docs
weight: 10
url: /ko/java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

오디오 문서를 정의합니다. 다음 유형을 포함합니다: , , , , , , , , , 오디오 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/audio/)를 클릭하세요.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [AudioFileType()](#AudioFileType--) | 직렬화 생성자 |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Mp3](#Mp3) | .mp3 확장자를 가진 파일은 MPEG-1 오디오 레이어 III 또는 MPEG-2 오디오 레이어 III를 기반으로 하는 디지털 인코딩 오디오 파일 형식입니다. |
|
|  | [Aac](#Aac) | AAC(Advanced Audio Coding)는 손실 압축을 기반으로 하는 디지털 오디오 코딩 표준을 의미합니다. |
|
|  | [Aiff](#Aiff) | AIFF(Audio Interchange File Format)는 1998년 Apple에서 개발한 비압축 오디오 파일 형식이며, EA IFF 85를 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/audio/aiff/)를 클릭하세요. |
|
|  | [Flac](#Flac) | FLAC(Free Lossless Audio Codec)는 Xiph.Org Foundation에서 개발한 무손실 압축 오디오 코딩 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/audio/flac/)를 클릭하세요. |
|
|  | [M4a](#M4a) | M4A 파일 형식은 손실 압축으로 알려진 AAC(Advanced Audio Coding)를 사용하여 만든 오디오 파일입니다. |
|
|  | [Wma](#Wma) | .wma 확장자를 가진 파일은 Advanced Systems Format(ASF) 형식으로 저장된 오디오 파일을 나타냅니다. |
|
|  | [Ac3](#Ac3) | .ac3 확장자를 가진 파일은 Dolby Laboratories에서 도입한 Audio Codec 3 파일입니다. |
|
|  | [Ogg](#Ogg) | OGG는 .ogg 확장자로 저장되는 Ogg Vorbis 압축 오디오 파일입니다. |
|
|  | [Wav](#Wav) | WAV는 WAVE(Waveform Audio File Format)로 알려져 있으며, 디지털 오디오 파일을 저장하기 위한 Microsoft\u2019s Resource Interchange File Format(RIFF) 사양의 하위 집합입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


직렬화 생성자


### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


.mp3 확장자를 가진 파일은 MPEG-1 Audio Layer III 또는 MPEG-2 Audio Layer III를 기반으로 하는 디지털 인코딩 오디오 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/audio/mp3/)를 클릭하세요.


### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC(Advanced Audio Coding)는 손실 압축을 기반으로 하는 오디오 파일을 나타내는 디지털 오디오 코딩 표준을 의미합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/audio/aac/)를 클릭하세요.


### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


AIFF(Audio Interchange File Format)는 1998년 Apple에서 개발한 비압축 오디오 파일 형식이며, EA IFF 85를 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/audio/aiff/)를 클릭하세요.


### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC(Free Lossless Audio Codec)는 Xiph.Org Foundation에서 개발한 무손실 압축 오디오 코딩 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/audio/flac/)를 클릭하세요.


### M4a {#M4a}
```
public static final AudioFileType M4a
```


M4A 파일 형식은 손실 압축으로 알려진 AAC(Advanced Audio Coding)를 사용하여 만든 오디오 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/audio/m4a/)를 클릭하세요.


### Wma {#Wma}
```
public static final AudioFileType Wma
```


.wma 확장자를 가진 파일은 Advanced Systems Format(ASF) 형식으로 저장된 오디오 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/audio/wma/)를 클릭하세요.


### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


.ac3 확장자를 가진 파일은 Dolby Laboratories에서 도입한 Audio Codec 3 파일이며, 최대 6채널 오디오 출력을 포함할 수 있는 오디오 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/audio/ac3/)를 클릭하세요.


### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG는 .ogg 확장자로 저장되는 Ogg Vorbis 압축 오디오 파일이며, 오디오 데이터를 저장하고 아티스트 및 트랙 정보, 메타데이터 등을 포함할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/audio/ogg/)를 클릭하세요.


### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV는 WAVE(Waveform Audio File Format)로 알려져 있으며, 디지털 오디오 파일을 저장하기 위한 Microsoft\u2019s Resource Interchange File Format(RIFF) 사양의 하위 집합입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/audio/ogg/)를 클릭하세요.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


파일 유형에 대한 기본 변환 옵션을 준비했습니다


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
