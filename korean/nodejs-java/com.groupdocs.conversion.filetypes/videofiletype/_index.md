---
title: "VideoFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "비디오 문서를 정의합니다. 다음 유형을 포함합니다        비디오 형식에 대해 자세히 알아보려면 여기에서 확인하세요."
type: docs
weight: 26
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

비디오 문서를 정의합니다. 다음 유형을 포함합니다: , , , , , , , 비디오 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/video/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VideoFileType()](#VideoFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Mp4](#Mp4) | MP4(MPEG-4 Part 14의 약자)는 ISO/IEC 14496-12:2004를 기반으로 하며 QuickTime 파일 형식을 기반으로 하지만 초기 객체 기술자(IOD) 및 기타 MPEG 기능에 대한 지원을 공식적으로 지정하는 파일 형식입니다. |
| [Avi](#Avi) | AVI 파일 형식은 Microsoft에서 도입한 오디오 비디오 멀티미디어 컨테이너 파일 형식입니다. |
| [Flv](#Flv) | FLV(Flash Video)는 .flv 확장자를 가진 컨테이너 파일 형식입니다. |
| [Mkv](#Mkv) | MKV(Matroska Video)는 MOV 및 AVI 형식과 유사한 멀티미디어 컨테이너이지만 동일 파일에서 여러 오디오 및 자막 트랙을 지원합니다. |
| [Mov](#Mov) | MOV 또는 QuickTime 파일 형식은 Apple에서 개발한 멀티미디어 컨테이너이며, 하나 이상의 트랙을 포함하고 각 트랙은 특정 유형의 데이터를 보유합니다(예:). |
| [Webm](#Webm) | .webm 확장자를 가진 파일은 오픈 소스이며 로열티가 없는 WebM 파일 형식을 기반으로 하는 비디오 파일입니다. |
| [Wmv](#Wmv) | Windows Media Video는 Microsoft에서 개발한 압축 비디오 형식입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


직렬화 생성자

### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4(MPEG-4 Part 14의 약자)는 ISO/IEC 14496-12:2004를 기반으로 하며 QuickTime 파일 형식을 기반으로 하지만 초기 객체 기술자(IOD) 및 기타 MPEG 기능에 대한 지원을 공식적으로 지정하는 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/video/mp4/

### Avi {#Avi}
```
public static final VideoFileType Avi
```


AVI 파일 형식은 Microsoft에서 도입한 오디오 비디오 멀티미디어 컨테이너 파일 형식이며, XVid 및 DivX와 같은 여러 코덱(코더/디코더)을 사용해 생성 및 압축된 오디오와 비디오 데이터를 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/video/avi/

### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV(Flash Video)는 .flv 확장자를 가진 컨테이너 파일 형식입니다. FLV는 Adobe Flash Player 또는 Adobe Air를 사용하여 인터넷을 통해 오디오/비디오 콘텐츠를 전달하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/video/flv/

### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV(Matroska Video)는 MOV 및 AVI 형식과 유사한 멀티미디어 컨테이너이지만 동일 파일에서 여러 오디오 및 자막 트랙을 지원합니다. MKV 파일은 비디오에 사용되는 Matroska 멀티미디어 컨테이너 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/video/mkv/

### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV 또는 QuickTime 파일 형식은 Apple에서 개발한 멀티미디어 컨테이너이며, 하나 이상의 트랙을 포함하고 각 트랙은 비디오, 오디오, 텍스트 등 특정 유형의 데이터를 보유합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/video/mov/

### Webm {#Webm}
```
public static final VideoFileType Webm
```


.webm 확장자를 가진 파일은 오픈 소스이며 로열티가 없는 WebM 파일 형식을 기반으로 하는 비디오 파일입니다. 웹에서 비디오를 공유하도록 설계되었으며 비디오 및 오디오 형식을 포함한 파일 컨테이너 구조를 정의합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/video/webm//

### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video는 Microsoft에서 개발한 압축 비디오 형식이며, 영화 및 텔레비전 엔지니어 협회(SMPTE)의 표준화 이후 WMV는 현재 오픈 표준 형식으로 간주됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/video/wmv/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


파일 유형에 대한 기본 변환 옵션을 준비했습니다.

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
