---
title: "SpreadsheetLoadOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "Spreadsheet 문서를 로드하기 위한 옵션을 제공합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/
is_root: false
weight: 440
---


## SpreadsheetLoadOptions class

Spreadsheet 문서를 로드하기 위한 옵션을 제공합니다.

SpreadsheetLoadOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/__init__/) | 새 인스턴스를 초기화합니다 [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/). |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | 현재 인스턴스를 복제합니다. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 두 객체 인스턴스가 같은지 여부를 결정합니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 기본 해시 함수로 사용됩니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | 이 속성은 시트의 모든 열 내용이 결과에서 단일 페이지로 렌더링되는지 여부를 결정합니다. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | 변환 시 행이 자동 맞춤됩니다. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | 이 속성은 셀 관련 객체를 수정할 때 Excel 파일 제한이 확인되는지 여부를 결정합니다. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_built_in_document_properties/) | ClearBuiltInDocumentProperties 속성은 스프레드시트를 로드할 때 내장 문서 속성이 지워지는지 여부를 결정합니다. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_custom_document_properties/) | ClearCustomDocumentProperties 속성. |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | 워크시트를 페이지로 분할하는 데 사용되는 페이지당 열 수입니다; 기본값은 0이며, 페이지 매김을 비활성화합니다. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owned/) | 이 속성은 [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/)를 구현하며 기본값은 False입니다. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owner/) | 이 속성은 [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/)를 구현합니다. 기본값은 True입니다. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | 스프레드시트가 아닌 형식으로 변환할 때 변환할 범위, 예: "D1:F8". |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | 파일이 로드될 때 사용되는 시스템 문화 정보입니다. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/default_font/) | 스프레드시트 문서의 기본 글꼴입니다. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/depth/) | 문서 컨테이너 로드 옵션의 깊이입니다. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/font_substitutes/) | 스프레드시트 문서를 변환할 때 사용되는 글꼴 대체입니다. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/format/) | 입력 문서 파일 유형입니다. |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | 이 속성은 수식 계산 오류를 무시할지 여부를 나타냅니다. 오류는 지원되지 않는 함수, 외부 링크 등일 수 있습니다. 기본값은 False입니다. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/margin_settings/) | 여백 설정. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | 이 속성은 각 시트의 내용이 PDF 문서에서 단일 페이지로 변환되는지 여부를 나타냅니다. 기본값은 True입니다. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | PDF로 변환할 때 True로 설정하면 인쇄 품질보다 파일 크기를 줄이는 방향으로 변환이 최적화됩니다. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | 보호된 문서의 보호를 해제하는 데 사용되는 비밀번호입니다. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | PDF로 변환할 때 문서 구조를 보존해야 하는지 여부를 나타내는 플래그(기본값은 False). |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | 시트와 함께 주석이 인쇄되는 방식입니다. 기본값은 PrintNoComments입니다. |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | 문서를 로드하기 전에 글꼴 폴더가 재설정됩니다. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | 워크시트를 페이지로 분할하는 데 사용되는 페이지당 행 수이며, 기본값 0은 페이지 매김이 없음을 의미합니다. |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | 변환할 시트 인덱스 목록입니다. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | 변환할 시트 이름. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Excel 파일을 변환할 때 눈금선을 표시하는 옵션. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Excel 파일을 변환할 때 숨겨진 시트를 표시하는 옵션. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/size_settings/) | 크기 설정은 [`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)에 정의된 대로입니다. |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | 변환 시 빈 행과 열을 건너뛰는 설정. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_external_resources/) | 이 속성은 [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/)를 구현합니다. |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | 스프레드시트 문서를 변환할 때 바닥글을 건너뛰는지 여부를 결정하는 속성. 기본값: False. |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | 스프레드시트 문서를 변환할 때 헤더를 건너뛰는 옵션. 기본값: False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/whitelisted_resources/) | 허용된 리소스는 [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/)에 정의됩니다. |

### 또 보기
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
