---
title: CompressionFileType
second_title: .NET API 참조용 GroupDocs.Conversion
description: 압축 형식을 정의합니다. 다음 파일 형식을 포함합니다. Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . 압축 형식에 대해 자세히 알아보기여기https//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /ko/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

압축 형식을 정의합니다. 다음 파일 형식을 포함합니다. [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . 압축 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | 직렬화 생성자 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 형식 description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 개체를 다른 개체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수 역할을 합니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2는 주로 UNIX 또는 Linux 시스템에서 BZIP2 오픈 소스 압축 방법을 사용하여 생성된 압축 파일입니다. 단일 파일 압축에 사용되며 여러 파일을 보관하기 위한 것이 아닙니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | 확장자가 .cab인 파일은 시스템 파일 범주에 속하는 Windows 캐비닛 파일에 속합니다. LZX, Quantum, ZIP 등 압축 데이터 알고리즘을 지원하는 Microsoft Windows 버전에서 아카이브 파일 형식으로 저장되는 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio는 일반 파일 아카이버 유틸리티 및 관련 파일 형식입니다. 주로 Unix 계열 컴퓨터 운영 체제에 설치됩니다. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | GZ 파일은 표준 gzip(GNU zip) 압축 알고리즘을 사용하여 생성된 압축 아카이브입니다. 여기에는 여러 압축 파일, 디렉토리 및 파일 스텁이 포함될 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Gzip 파일은 표준 gzip(GNU zip) 압축 알고리즘을 사용하여 생성된 압축 아카이브입니다. 여기에는 여러 압축 파일, 디렉토리 및 파일 스텁이 포함될 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | 확장자가 .lz인 파일은 압축을 위한 무료 명령줄 도구인 Lzip으로 만든 압축된 아카이브 파일입니다. 지원 파일을 압축하기 위한 연결을 지원합니다. LZ 파일은 미디어 유형이 application/lzip이며 BZ2. 보다 높은 압축률을 지원합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | 확장자가 .lzma인 파일은 LZMA(Lempel-Ziv-Markov chain Algorithm) 압축 방식을 사용하여 만든 압축 아카이브 파일입니다. 이들은 주로 Unix 운영 체제에서 발견/사용되며 파일 크기를 최소화하기 위한 ZIP과 같은 다른 압축 알고리즘과 유사합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | 확장자가 .rar인 파일은 압축 또는 일반 형식으로 정보를 저장하기 위해 생성된 아카이브 파일입니다. Roshal ARchive 파일 형식을 나타내는 RAR. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z는 압축률이 높은 파일 및 폴더를 압축하기 위한 아카이빙 형식입니다. 모든 압축 및 암호화 알고리즘을 사용할 수 있는 오픈 소스 아키텍처를 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | 확장자가 .tar인 파일은 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 파일과 폴더를 아카이브에 추가하는 기능을 통해 여러 파일이 압축되지 않은 형식으로 저장됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ는 LZMA2 압축 알고리즘을 활용하는 압축 파일 형식입니다. 널리 사용되는 gzip 및 bzip2 형식을 대체하도록 설계되었으며 이전 표준에 비해 많은 이점을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | AZ 파일은 UNIX 압축 데이터 파일에 속하는 파일의 범주입니다. 압축된 Unix 파일은 Z 파일의 가장 널리 사용되고 널리 사용되는 확장자 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | 확장명이 .zip인 파일은 하나 이상의 파일 또는 디렉터리를 보관할 수 있는 아카이브입니다. 아카이브는 ZIP 파일 크기를 줄이기 위해 포함된 파일에 압축을 적용할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/zip/) . |

### 또한보십시오

* class [FileType](../filetype)
* 네임스페이스 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
