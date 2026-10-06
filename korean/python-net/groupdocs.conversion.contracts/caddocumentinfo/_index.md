---
title: "CadDocumentInfo 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "Cad 문서 메타데이터를 포함합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Cad 문서 메타데이터를 포함합니다.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

명시적인 [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/)이 없으면 해당 시트는 모델 공간이며, 이는 항상 플롯 가능하고 따라서 항상 시트이며, 저장된 페이지 설정에 양의 너비와 높이가 있는 모든 종이 공간 레이아웃과, [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/)에 의해 제한됩니다. 명시적인 레이아웃 이름이 우선 적용되어, 시트는 그때 도면이 가지고 있는 제공된 이름들에 따라 순서대로 매치되며, 범위나 페이지 설정이 이를 걸러내지 않습니다.

DWF의 경우 게시된 페이지 집합이 보고됩니다. 하나 미만의 카운트는 0이며, 이는 요청된 범위가 해당 도면의 시트와 일치하지 않을 때 보고됩니다: 메타데이터는 여전히 도면을 설명하고, 0은 범위가 아무 것도 선택하지 않음을 의미하며, 도면이 무엇을 포함하고 있는지 묻는 호출자를 실패시키지는 않습니다. 동일한 로드 옵션으로 변환을 시도하면 실패합니다.

따라서 카운트는 [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/)의 크기가 아니며, 이 속성은 시트로 게시될 수 없는 경우를 포함하여 도면이 가지고 있는 모든 플롯 구성을 나열하고, 특정 변환이 생성하는 페이지 수를 예측하지도 않습니다.

CadDocumentInfo 형식은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | 문서 생성 날짜. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | 문서 형식. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | CAD 문서의 높이. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | 문서의 레이어. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | 문서의 레이아웃. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | 문서 페이지 수. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | 현재 문서 정보에 대해 검색할 수 있는 모든 속성의 열거형. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | 문서 크기(바이트). |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | CAD 문서의 너비. |

### 또 보기
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
