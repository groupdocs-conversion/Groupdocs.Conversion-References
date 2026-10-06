---
title: "WordProcessingLoadOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "WordProcessing 문서를 로드하기 위한 옵션을 제공합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

WordProcessing 문서를 로드하기 위한 옵션을 제공합니다.

폰트 처리 파이프라인:

1단계 - 글꼴 대체 (문서 로드 중):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

2단계 - 글꼴 교체 (문서 로드 후):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

WordProcessingLoadOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | 새 인스턴스를 초기화합니다 [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

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
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | auto_detect_rtl_direction 속성은 주로 오른쪽에서 왼쪽으로 쓰여진 텍스트를 가진 단락 및 실행의 bidi 플래그가 변환 전에 복구되는지를 결정합니다. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | 북마크 옵션. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | Word 처리 문서를 로드할 때 내장 문서 속성이 지워지는지를 나타내는 플래그. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | ClearCustomDocumentProperties 속성. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | 주석 표시 모드는 출력 문서에서 주석이 어떻게 표시되는지를 지정합니다. 기본값은 `ShowInBalloons`입니다. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | 이 속성은 [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/)을 구현합니다. 기본값은 False입니다. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | convert_owner 플래그는 문서 소유자를 변환할지 여부를 나타냅니다. 기본값은 True입니다. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | WordProcessing 문서의 기본 글꼴. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | 문서 컨테이너 로드 옵션의 깊이. 기본값은 1입니다. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | embed_true_type_fonts 속성은 True Type 글꼴이 출력 문서에 포함되는지를 결정합니다. 기본값은 True입니다. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | 이 속성은 시스템 FontConfig을 기반으로 누락된 글꼴을 자동으로 대체하도록 합니다. 기본값은 False입니다. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | 문서 내 FontInfo를 기반으로 누락된 글꼴을 자동으로 대체하도록 하는 플래그입니다. 기본값: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | 이 속성은 글꼴 이름을 기반으로 누락된 글꼴이 자동으로 대체되는지를 나타냅니다. 기본값: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | WordProcessing 문서를 변환할 때 사용되는 글꼴 대체 목록. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | 문서 로드와 글꼴 대체가 완료된 후 적용되는 글꼴 변환으로, 성공적으로 로드된 글꼴을 포함한 문서 내 모든 글꼴을 수정할 수 있습니다. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | 입력 문서 파일 유형입니다. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | hide_word_tracked_changes 속성은 Word 문서의 마크업 및 변경 추적을 숨깁니다. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | WordProcessing 문서의 하이픈 옵션. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | keep_date_field_original_value 속성은 날짜 필드의 원래 값이 유지되는지를 결정합니다. 기본값은 False입니다. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | 여백 설정. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | 변환된 문서의 페이지 번호 생성 플래그 (기본값: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | 보호된 문서의 보호를 해제하기 위한 비밀번호. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | PDF로 변환할 때 문서 구조를 보존해야 하는지 여부를 나타내는 플래그(기본값은 False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | Microsoft Word 양식 필드가 결과 PDF에서 양식 필드로 보존되는지 또는 텍스트로 변환되는지를 나타내는 속성입니다. 기본값은 False입니다. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | 전체 댓글 작성자 이름이 True로 설정될 때 댓글에 표시됩니다. 기본값은 False입니다. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | WordProcessing 문서의 크기 설정([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | 문서를 로드할 때 외부 리소스를 건너뛸지 여부를 결정하는 플래그입니다. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | 로드 후 필드를 업데이트하는 옵션입니다. 기본값: False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | 로드 후 페이지 레이아웃이 업데이트됩니다. 기본값: False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | 텍스트 셰이퍼를 사용하여 커닝 표시를 개선할지 여부를 나타내는 속성입니다. 기본값은 False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | 외부 콘텐츠 로드를 위한 허용된 리소스로, [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/)를 구현합니다. |

### 예제

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
`WordProcessingLoadOptions`를 사용하는 작업 가이드:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### 또 보기
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
