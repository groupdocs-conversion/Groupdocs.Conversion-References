---
title: "XmlLoadOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "XML 문서를 로드하기 위한 옵션."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/xmlloadoptions/
is_root: false
weight: 590
---


## XmlLoadOptions class

XML 문서를 로드하기 위한 옵션.

XmlLoadOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/__init__/) | 새 인스턴스를 초기화합니다 [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/). |

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
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/custom_css_style/) | 변환 중에 문서에 적용될 사용자 정의 CSS 스타일. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/format/) | 입력 문서 파일 유형입니다. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/margin_settings/) | 페이지 여백 설정. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/orientation_settings/) | 페이지 방향 설정. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_layout_options/) | 문서를 로드할 때 적용할 페이지 레이아웃 스케일링. 기본값: 없음. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_numbering/) | 변환된 문서의 페이지 번호 생성 플래그 (기본값: False). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/size_settings/) | 페이지 크기 설정. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/) | 이 속성은 외부 리소스가 로드되는지 여부를 나타냅니다. |
| [use_as_data_source](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/use_as_data_source/) | XML 문서는 데이터 소스로 사용됩니다. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/whitelisted_resources/) | 항상 로드되는 외부 리소스. |
| [xsl_fo_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xsl_fo_factory/) | XSL-FO 마크업 파일을 사용하여 XML을 변환하기 위한 XSL-FO 문서 스트림. |
| [xslt_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xslt_factory/) | XML을 HTML로 변환하기 위해 XSL 변환을 수행하는 XSLT 문서 스트림. |
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | HTML의 기본 경로/URL입니다. ([`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)에서 상속됨) |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | 요청 헤더를 구성하는 동작이며, 첫 번째 매개변수는 Uri입니다. ([`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)에서 상속됨) |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Uri에 대한 자격 증명 제공자입니다. ([`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)에서 상속됨) |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | 웹 문서를 로드할 때 사용할 인코딩입니다. None으로 설정하면 인코딩이 문서의 문자 집합 속성에서 결정됩니다. ([`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)에서 상속됨) |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | HTML 렌더링 모드는 HTML 콘텐츠가 렌더링되는 방식을 제어합니다. 기본값: AbsolutePositioning. ([`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)에서 상속됨) |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | 외부 리소스를 로드하는 시간 제한입니다. ([`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)에서 상속됨) |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | 이 속성은 변환에 PDF를 사용할지 여부를 나타냅니다 (기본값: False). ([`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)에서 상속됨) |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | 변환 전에 문서의 `<body>` 태그에 적용되는 백분율 형태의 줌 레벨로, 문서의 시각적 모습을 스케일링합니다. ([`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)에서 상속됨) |

### 또 보기
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
