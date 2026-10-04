---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "워드 프로세싱 파일을 정의합니다. 이 파일은 일반 텍스트 또는 리치 텍스트 형식으로 사용자 정보를 포함합니다. 일반 텍스트 파일 형식은 서식이 없는 텍스트이며 글꼴이나 페이지 설정 등을 적용할 수 없습니다. 반면 리치 텍스트 파일 형식은 글꼴 종류, 스타일(굵게, 기울임, 밑줄 등), 페이지 여백, 제목, 글머리표 및 번호 매기기 등 여러 서식 옵션을 허용합니다. 다음 파일 유형을 포함합니다 Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt Md./wordprocessingfiletype/md. 워드 프로세싱 형식에 대해 자세히 알아보려면 여기 https//wiki.fileformat.com/wordprocessing을 방문하십시오."
type: docs
weight: 1280
url: /ko/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

워드 프로세싱 파일을 정의합니다. 이 파일은 일반 텍스트 또는 리치 텍스트 형식으로 사용자 정보를 포함합니다. 일반 텍스트 파일 형식은 서식이 없는 텍스트이며 글꼴이나 페이지 설정 등을 적용할 수 없습니다. 반면 리치 텍스트 파일 형식은 글꼴 종류, 스타일(굵게, 기울임, 밑줄 등), 페이지 여백, 제목, 글머리표 및 번호 매기기 등 여러 서식 옵션을 허용합니다. 다음 파일 유형을 포함합니다: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). 워드 프로세싱 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing)를 클릭하십시오.

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
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 유형 설명 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 패밀리 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | .doc 확장자를 가진 파일은 Microsoft Word 또는 기타 워드 프로세서에서 생성된 이진 파일 형식의 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/doc)를 클릭하십시오. |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM 파일은 매크로 실행 기능이 포함된 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/docm)를 클릭하십시오. |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX는 Microsoft Word 문서의 잘 알려진 형식입니다. 2007년 Microsoft Office 2007 출시와 함께 도입되었으며, 이 새로운 문서 형식의 구조는 기존의 순수 이진 형태에서 XML과 이진 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/docx)를 클릭하십시오. |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | .DOT 확장자를 가진 파일은 Microsoft Word에서 만든 템플릿 파일로, 이후 DOC 또는 DOCX 파일을 생성할 때 미리 서식이 지정된 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dot)를 클릭하십시오. |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | DOTM 확장자를 가진 파일은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dotm)를 클릭하십시오. |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | .DOTX 확장자를 가진 파일은 Microsoft Word에서 만든 템플릿 파일로, 이후 DOCX 파일을 생성할 때 미리 서식이 지정된 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dotx)를 클릭하십시오. |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word는 ZIP 패키지 대신 평면 XML 파일에 저장된 Office Open XML WordprocessingML입니다. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Markdown 언어 방언으로 만든 텍스트 파일은 .MD 또는 .MARKDOWN 파일 확장자로 저장됩니다. MD 파일은 Markdown 언어를 사용하는 일반 텍스트 형식으로 저장되며, 들여쓰기, 표 서식, 글꼴 및 헤더와 같은 텍스트 서식 방법을 정의하는 인라인 텍스트 기호를 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/md)를 클릭하십시오. |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/odt)를 클릭하십시오. |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | OTT 확장자를 가진 파일은 OASIS의 OpenDocument 표준 형식을 준수하는 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/ott)를 클릭하십시오. |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Microsoft에서 도입하고 문서화한 Rich Text Format (RTF)은 애플리케이션 내에서 서식이 지정된 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/rtf)를 클릭하십시오. |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | TXT 확장자를 가진 파일은 줄 형태의 일반 텍스트를 포함하는 텍스트 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/txt)를 클릭하십시오. |

### 또 보기

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
