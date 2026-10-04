---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "압축 형식을 정의합니다. 다음 파일 유형을 포함합니다 Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. 압축 형식에 대해 자세히 알아보려면 here https//docs.fileformat.com/compression/ 를 방문하십시오."
type: docs
weight: 1080
url: /ko/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

압축 형식을 정의합니다. 다음 파일 유형을 포함합니다: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). 압축 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/) 를 클릭하십시오.

```csharp
public sealed class CompressionFileType : FileType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 유형 설명 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 패밀리 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | 단일 압축 파일에서 형식이 여러 파일/폴더를 지원하는지 정의합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 객체를 다른 객체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | `[`Equals`](../../groupdocs.conversion.contracts/enumeration/equals)`를 구현합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수로 사용됩니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | .aar 확장자를 가진 파일은 Apple Archive이며, macOS와 함께 제공되는 Apple의 컨테이너로 파일 및 폴더를 그룹화합니다. 각 항목은 개별적으로 압축되며, 대부분 LZFSE를 사용합니다. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | .alz 확장자를 가진 파일은 ESTsoft에서 만든 ALZip 아카이브이며, 한국에서 널리 사용되는 형식입니다. 항목은 비밀번호로 개별 암호화될 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/alz/)를 클릭하십시오. |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2는 주로 UNIX 또는 Linux 시스템에서 사용되는 BZIP2 오픈 소스 압축 방식을 사용해 생성된 압축 파일입니다. 단일 파일 압축에 사용되며 여러 파일을 아카이브하는 용도로는 적합하지 않습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/bz2/)를 클릭하십시오. |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | .cab 확장자를 가진 파일은 시스템 파일 범주에 속하는 Windows 캐비닛 파일입니다. 이는 LZX, Quantum, ZIP과 같은 압축 데이터 알고리즘을 지원하는 Microsoft Windows 버전에서 아카이브 파일 형식으로 저장되는 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/system/cab/)를 클릭하십시오. |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio는 일반 파일 아카이버 유틸리티 및 관련 파일 형식이며, 주로 Unix 계열 운영 체제에 설치됩니다. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | GZ 파일은 표준 gzip(GNU zip) 압축 알고리즘을 사용해 만든 압축 아카이브입니다. 여러 압축 파일, 디렉터리 및 파일 스텁을 포함할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/gz/)를 클릭하십시오. |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Gzip 파일은 표준 gzip(GNU zip) 압축 알고리즘을 사용해 만든 압축 아카이브입니다. 여러 압축 파일, 디렉터리 및 파일 스텁을 포함할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/gz/)를 클릭하십시오. |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | .iso 확장자를 가진 파일은 CD나 DVD와 같은 광학 디스크 전체 데이터를 나타내는 비압축 아카이브 디스크 이미지 파일입니다. ISO-9660 표준을 기반으로 하며, ISO 이미지 파일 형식은 디스크 데이터와 그 안에 저장된 파일 시스템 정보를 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/iso/)를 클릭하십시오. |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | .lzh 및 .lha 확장자를 가진 파일은 일반적으로 아카이브 압축 파일 형식과 관련됩니다. 이 파일 형식은 ZIP, RAR 등 다른 파일 압축 형식과 동일합니다. 이러한 파일 형식의 주요 목적은 크기를 줄여 쉽게 전송하고 압축된 형태로 함께 보관하기 위함입니다. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | .lz 확장자를 가진 파일은 Lzip으로 만든 압축 아카이브 파일이며, 이는 무료 명령줄 압축 도구입니다. 파일 연결을 지원하여 지원 파일을 압축할 수 있습니다. LZ 파일은 미디어 타입 application/lzip을 가지며 BZ2보다 높은 압축 비율을 지원합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/bz2/)를 클릭하십시오. |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | .lz4 확장자를 가진 파일은 LZ4 압축을 지원하는 응용 프로그램/유틸리티로 만든 압축 아카이브 파일입니다. LZ4 알고리즘은 속도와 압축 비율 사이의 균형에 중점을 둡니다. 압축된 LZ4 아카이브는 LZ4 명령줄 유틸리티를 사용해 생성하고 동일한 도구로 해제할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/lz4/)를 클릭하십시오. |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | .lzma 확장자를 가진 파일은 LZMA(Lempel-Ziv-Markov chain Algorithm) 압축 방식을 사용해 만든 압축 아카이브 파일입니다. 주로 Unix 운영 체제에서 사용되며 ZIP과 유사하게 파일 크기를 최소화합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/lzma/)를 클릭하십시오. |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | .rar 확장자를 가진 파일은 압축 또는 일반 형태로 정보를 저장하기 위해 만든 아카이브 파일입니다. RAR은 Roshal ARchive 파일 형식을 의미합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/rar/)를 클릭하십시오. |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z는 높은 압축 비율로 파일 및 폴더를 압축하는 아카이브 형식입니다. 오픈 소스 아키텍처를 기반으로 하여 다양한 압축 및 암호화 알고리즘을 사용할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/7z/)를 클릭하십시오. |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | .tar 확장자를 가진 파일은 Unix 기반 유틸리티로 만든 아카이브이며, 하나 이상의 파일을 모으는 데 사용됩니다. 여러 파일이 압축되지 않은 형식으로 저장되며 파일 및 폴더를 아카이브에 추가할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/tar/)를 클릭하십시오. |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | uuencode된 아카이브는 Unix-to-Unix 인코딩 방식(uuencode)으로 인코딩된 파일 또는 파일 모음입니다. 이 인코딩 방법은 이진 데이터를 텍스트 형식으로 변환하여 이메일과 같이 텍스트만 지원하는 채널을 통해 파일을 전송하기 쉽게 합니다. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | .wim 확장자를 가진 파일은 Windows Imaging Format 아카이브로, Microsoft가 Windows 배포에 사용하는 파일 기반 디스크 이미지입니다. 하나의 아카이브에 하나 이상의 이미지가 포함되며, 각 파일은 이미지가 몇 개이든 한 번만 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/disc-and-media/wim/)를 클릭하십시오. |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | .xar 확장자를 가진 파일은 eXtensible ARchive이며, 압축된 XML로 저장된 목차를 중심으로 구성된 형식입니다. macOS 설치 패키지를 배포하는 데 사용되며 각 항목을 개별적으로 압축합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/xar/)를 클릭하십시오. |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ는 LZMA2 압축 알고리즘을 활용한 압축 파일 형식입니다. 기존의 gzip 및 bzip2 형식을 대체하도록 설계되었으며, 이러한 오래된 표준에 비해 여러 장점을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/xz/)를 클릭하십시오. |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Z 파일은 UNIX 압축 데이터 파일에 속하는 파일 종류입니다. 압축된 Unix 파일은 Z 파일 확장자 유형 중 가장 인기 있고 널리 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/z/)를 클릭하십시오. |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | .zip 확장자를 가진 파일은 하나 이상의 파일이나 디렉터리를 포함할 수 있는 아카이브이며, 포함된 파일에 압축을 적용해 ZIP 파일 크기를 줄일 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/zip/)를 클릭하십시오. |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | ZST 파일은 Zstandard (zstd) 압축 알고리즘으로 생성된 압축 파일입니다. 이 알고리즘에 의해 무손실 압축으로 만들어진 압축 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/compression/zst/)를 클릭하십시오. |

### 또 보기

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
