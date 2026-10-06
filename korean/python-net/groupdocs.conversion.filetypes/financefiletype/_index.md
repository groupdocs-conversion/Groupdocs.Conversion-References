---
title: "FinanceFileType 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "재무 문서 유형을 정의합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

재무 문서 유형을 정의합니다.

다음 유형을 포함합니다: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). 여기에서 금융 형식에 대해 자세히 알아보세요: https://docs.fileformat.com/finance/.

FinanceFileType 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | 직렬화를 위해 FinanceFileType을 초기화합니다. |

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
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL은 전 세계적으로 널리 사용되는 디지털 비즈니스 보고를 위한 개방형 국제 표준입니다. XML 기반 언어로, XBRL 요소(태그라고도 함)를 사용하여 비즈니스 데이터의 각 항목을 설명하고 보고서 정렬 및 분석을 위한 데이터를 구성합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | iXBRL 내부에서는 XBRL 내용이 XML 태그를 사용하는 xHTML 파일 형식으로 감싸져 있습니다. XBRL과 마찬가지로 iXBRL 파일의 루트 요소는 XBRL입니다. XHTML 형식은 다양한 문서 유형 및 모듈의 컬렉션으로 내용을 나타냅니다. XHTML의 모든 파일은 XML 파일 형식을 기반으로 하며 XML 문서 표준을 준수합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange(OFX)는 Microsoft의 Open Financial Connectivity(OFC)와 Intuit의 Open Exchange 파일 형식에서 발전한 금융 정보를 교환하기 위한 데이터 스트림 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 알 수 없는 파일 유형 ([`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |

### 또 보기
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
