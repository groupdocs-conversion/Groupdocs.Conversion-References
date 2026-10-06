---
title: "FontTransformation 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "문서 로드 및 폰트 대체 후 적용되는 폰트 속성을 포함한 폰트 변환 구성을 설명합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

문서 로드 및 폰트 대체 후 적용되는 폰트 속성을 포함한 폰트 변환 구성을 설명합니다.

FontTransformation 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | 정확한 글꼴 일치를 사용하여 글꼴 변환을 생성합니다(크기와 스타일이 일치해야 함). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | 이름만으로 글꼴 변환을 생성하며, 모든 크기와 스타일에 일치하고, 교체 글꼴이 원본 글꼴의 크기와 스타일을 유지합니다. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | 유연한 일치 옵션으로 글꼴 변환을 생성합니다. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 두 객체 인스턴스가 같은지 여부를 결정합니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 기본 해시 함수로 사용됩니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | 이 속성은 원본 글꼴 이름에 대해 모든 글꼴 크기가 일치하는지(true) 또는 `OriginalFont`에 지정된 정확한 글꼴 크기만 일치하는지(false)를 나타냅니다. |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | 이 속성은 원본 글꼴의 모든 글꼴 스타일(굵게, 기울임, 밑줄)이 일치하는지(True) 또는 `OriginalFont`에 지정된 정확한 글꼴 스타일이 필요한지(False)를 결정합니다. |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | 일치 및 교체할 원본 글꼴 사양. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | 교체 글꼴 사양. |

### 또 보기
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
