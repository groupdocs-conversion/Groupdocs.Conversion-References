---
title: "WordProcessingFileType 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "WordProcessingFileType 클래스는 일반 텍스트와 리치 텍스트 변형을 포함하는 워드 프로세싱 파일 형식을 정의합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/
is_root: false
weight: 230
---


## WordProcessingFileType class

WordProcessingFileType 클래스는 일반 텍스트와 리치 텍스트 변형을 포함하는 워드 프로세싱 파일 형식을 정의합니다.

일반 텍스트 파일은 서식이 적용되지 않은 텍스트로, 글꼴이나 페이지 설정이 없습니다. 리치 텍스트 파일은 글꼴 종류, 스타일(굵게, 기울임, 밑줄), 페이지 여백, 제목, 글머리표, 번호 매기기 및 기타 기능과 같은 서식 옵션을 지원합니다.

- [`WordProcessingFileType.Doc`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/doc/)
- [`WordProcessingFileType.Docm`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docm/)
- [`WordProcessingFileType.Docx`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/)
- [`WordProcessingFileType.Dot`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dot/)
- [`WordProcessingFileType.Dotm`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dotm/)
- [`WordProcessingFileType.Dotx`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dotx/)
- [`WordProcessingFileType.Odt`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/odt/)
- [`WordProcessingFileType.Ott`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/ott/)
- [`WordProcessingFileType.Rtf`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/rtf/)
- [`WordProcessingFileType.Txt`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/txt/)
- [`WordProcessingFileType.Md`](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/md/)

Word Processing 형식에 대해 자세히 알아보려면 여기에서 확인하십시오: https://wiki.fileformat.com/word-processing

WordProcessingFileType 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/__init__/) | 직렬화를 위해 WordProcessingFileType을 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | 현재 객체를 다른 객체와 비교합니다. ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/)에 정의된 동등성 비교를 구현합니다. (`[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (`[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | 제공된 파일 확장자에 대한 FileType을 가져옵니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | 지정된 file_name에 대한 FileType을 반환합니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | 제공된 문서 스트림에 대한 FileType을 반환합니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (`[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | 기본 해시 함수를 제공합니다. ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | 파일 유형의 문자열 표현입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | 파일 유형 설명입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | 파일 확장자입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | 파일 패밀리입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | 파일 형식입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### 필드
| 필드 | 설명 |
| :- | :- |
| [DOC](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/doc/) | .doc 확장자를 가진 파일은 Microsoft Word 또는 기타 워드 프로세싱 문서에서 생성된 바이너리 파일 형식의 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOCM](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docm/) | DOCM 파일은 Microsoft Word 2007 이상에서 생성된 문서로 매크로 실행 기능을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOCX](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/) | DOCX는 Microsoft Word 문서의 잘 알려진 형식입니다. 2007년 Microsoft Office 2007 출시와 함께 도입된 이 새로운 문서 형식은 기존의 순수 바이너리 구조에서 XML과 바이너리 파일의 조합으로 구조가 변경되었습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOT](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dot/) | .DOT 확장자를 가진 파일은 Microsoft Word에서 추가 DOC 또는 DOCX 파일을 생성하기 위한 사전 서식 설정을 가진 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOTM](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dotm/) | DOTM 확장자를 가진 파일은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOTX](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/dotx/) | DOTX 확장자를 가진 파일은 Microsoft Word에서 추가 DOCX 파일을 생성하기 위한 사전 서식 설정을 가진 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [RTF](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/rtf/) | Microsoft에서 도입하고 문서화한 Rich Text Format(RTF)은 애플리케이션 내에서 사용되는 서식이 적용된 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [ODT](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/odt/) | ODT 파일은 OpenDocument Text 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [OTT](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/ott/) | OTT 확장자를 가진 파일은 OASIS의 OpenDocument 표준 형식에 따라 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기를 클릭하십시오. |
| [TXT](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/txt/) | .TXT 확장자를 가진 파일은 줄 형태의 일반 텍스트를 포함하는 텍스트 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기를 클릭하십시오. |
| [MD](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/md/) | Markdown 언어 방언으로 만든 텍스트 파일은 .MD 또는 .MARKDOWN 파일 확장자로 저장됩니다. MD 파일은 Markdown 언어를 사용하는 일반 텍스트 형식으로 저장되며, 여기에는 들여쓰기, 표 서식, 글꼴 및 헤더와 같은 텍스트 서식을 정의하는 인라인 텍스트 기호가 포함됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기를 클릭하십시오. |
| [FLAT_OPC](/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/flat_opc/) | Flat OPC Word는 ZIP 패키지 대신 평면 XML 파일에 저장된 Office Open XML WordprocessingML입니다. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 알 수 없는 파일 유형 ([`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # 입력 문서로 Converter를 인스턴스화합니다.
    with Converter("./business-plan.docx") as converter:
        # 변환 옵션을 정의합니다; 기본 출력 형식은 DOCX입니다.
        word_convert_options = WordProcessingConvertOptions()
        # 형식군 내에서 출력 형식을 DOCX에서 TXT로 변경합니다.
        word_convert_options.format = WordProcessingFileType.Txt

        # 입력 문서를 TXT로 변환합니다.
        converter.convert("./business-plan.txt", word_convert_options)

if __name__ == "__main__":
    specify_output_format()
```

### Guides
`WordProcessingFileType`을 사용하는 작업 가이드:

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### 또 보기
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
