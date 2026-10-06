---
title: "TxtLoadOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "Txt 문서를 로드하기 위한 옵션."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Txt 문서를 로드하기 위한 옵션.

일반 텍스트에 대한 글꼴 구성:

TXT 파일에는 글꼴 정보가 없으므로, 변환 중 일반 텍스트 내용을 렌더링할 글꼴을 지정하려면 DefaultTextFont를 사용합니다.

TxtLoadOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | 새 [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 두 객체 인스턴스가 같은지 여부를 결정합니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 기본 해시 함수로 사용됩니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | 변환 중 일반 텍스트 내용을 렌더링할 때 사용할 글꼴입니다. 기본값: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | 이 속성은 일반 텍스트 문서를 변환할 때 번호 매기기 목록 항목을 인식하는 방식을 지정합니다. 기본값은 True입니다. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | Txt 문서를 로드할 때 사용되는 인코딩입니다. None일 수 있습니다. 기본값은 None입니다. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | 입력 문서 파일 유형입니다. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | 선행 공백을 처리하기 위한 선호 옵션입니다. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/)에 정의된 여백 설정입니다. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | TXT 문서를 로드하기 위한 페이지 크기 옵션입니다. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | 후행 공백을 처리하기 위한 선호 옵션입니다. 기본값은 [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/)입니다. |

### 또 보기
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
