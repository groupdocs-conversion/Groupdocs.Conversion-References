---
title: "EBookFileType 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "EBook 문서를 정의합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.filetypes/ebookfiletype/
is_root: false
weight: 60
---


## EBookFileType class

EBook 문서를 정의합니다. 다음 파일 형식이 포함됩니다: [`EBookFileType.epub`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/epub/), [`EBookFileType.mobi`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/mobi/), [`EBookFileType.azw3`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/azw3/).

EBookFileType 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/__init__/) | 직렬화를 위해 새로운 [`EBookFileType`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/) 인스턴스를 초기화합니다. |

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
| [EPUB](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/epub/) | EPUB 확장자는 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. 이 형식은 현재 매우 일반화되어 많은 전자책 리더와 소프트웨어 애플리케이션에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [MOBI](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/mobi/) | MOBI 파일 형식은 가장 널리 사용되는 전자책 파일 형식 중 하나입니다. 이 형식은 기존 OEB(Open Ebook Format) 형식을 개선한 것이며 Mobipocket Reader의 독점 형식으로 사용되었습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [AZW3](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/azw3/) | AZW3는 Kindle Format 8(KF8)이라고도 하며, Amazon Kindle 기기를 위해 개발된 AZW 전자책 디지털 파일 형식의 수정 버전입니다. 이 형식은 이전 AZW 파일을 개선한 것이며 Kindle Fire 기기에서만 사용되며, 이전 파일 형식인 MOBI와 AZW와의 하위 호환성을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 알 수 없는 파일 유형 ([`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |

### 또 보기
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
