---
title: WordProcessingFileType
second_title: .NET API 참조용 GroupDocs.Conversion
description: 일반 텍스트 또는 리치 텍스트 형식의 사용자 정보를 포함하는 워드 프로세싱 파일을 정의합니다. 일반 텍스트 파일 형식에는 형식이 지정되지 않은 텍스트가 포함되며 글꼴이나 페이지 설정 등을 적용할 수 없습니다. 반대로 서식 있는 텍스트 파일 형식에서는 글꼴 유형 스타일굵게 기울임꼴 밑줄 등 페이지 여백 제목 글머리 기호 및 숫자 기타 여러 서식 기능 설정과 같은 서식 옵션을 사용할 수 있습니다. 다음 파일 형식을 포함합니다. Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log . 워드 프로세싱 형식에 대해 자세히 알아보기여기https//wiki.fileformat.com/wordprocessing .
type: docs
weight: 1090
url: /ko/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

일반 텍스트 또는 리치 텍스트 형식의 사용자 정보를 포함하는 워드 프로세싱 파일을 정의합니다. 일반 텍스트 파일 형식에는 형식이 지정되지 않은 텍스트가 포함되며 글꼴이나 페이지 설정 등을 적용할 수 없습니다. 반대로 서식 있는 텍스트 파일 형식에서는 글꼴 유형, 스타일(굵게, 기울임꼴, 밑줄 등), 페이지 여백, 제목, 글머리 기호 및 숫자, 기타 여러 서식 기능 설정과 같은 서식 옵션을 사용할 수 있습니다. 다음 파일 형식을 포함합니다. [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , Mobi , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . Log . 워드 프로세싱 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | 직렬화 생성자 |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | 확장자가 .doc인 파일은 Microsoft Word에서 생성된 문서 또는 이진 파일 형식의 기타 워드 프로세싱 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM 파일은 매크로 실행 기능이 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX는 Microsoft Word 문서의 잘 알려진 형식입니다. 2007년부터 Microsoft Office 2007 출시와 함께 도입된 이 새로운 문서 형식의 구조는 일반 바이너리에서 XML과 바이너리 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | 확장자가 .DOT인 파일은 Microsoft Word에서 추가 DOC 또는 DOCX 파일 생성을 위한 미리 포맷된 설정을 갖도록 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | 확장자가 DOTM인 파일은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | DOTX 확장자를 가진 파일은 추가 DOCX 파일 생성을 위해 미리 포맷된 설정을 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Markdown 언어 방언으로 생성된 텍스트 파일은 .MD 또는 .MARKDOWN 파일 확장자로 저장됩니다. MD 파일은 인라인 텍스트 기호를 포함하는 Markdown 언어를 사용하는 일반 텍스트 형식으로 저장되어 들여쓰기, 테이블 서식, 글꼴 및 헤더와 같은 텍스트 서식 지정 방법을 정의합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT 파일은 OpenDocument Text File 형식을 기반으로 하는 워드 프로세싱 응용 프로그램으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | OTT 확장자를 가진 파일은 OASIS의 OpenDocument 표준 형식을 준수하는 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Microsoft에서 도입하고 문서화한 RTF(서식 있는 텍스트 형식)는 응용 프로그램 내에서 사용하기 위해 형식이 지정된 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | 확장자가 .TXT인 파일은 라인 형태의 일반 텍스트를 포함하는 텍스트 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/txt) . |

### 또한보십시오

* class [FileType](../filetype)
* 네임스페이스 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
