---
title: "CsvLoadOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "CSV 문서를 로드하기 위한 옵션을 제공합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/csvloadoptions/
is_root: false
weight: 80
---


## CsvLoadOptions class

CSV 문서를 로드하기 위한 옵션을 제공합니다.

CsvLoadOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/__init__/) | 새 [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/) 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | 현재 인스턴스를 복제합니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 두 객체 인스턴스가 같은지 여부를 결정합니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 기본 해시 함수로 사용됩니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_built_in_document_properties/) | 이 속성은 문서에서 기본 메타데이터 속성을 제거합니다. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_custom_document_properties/) | 이 속성은 문서에서 사용자 정의 메타데이터 속성을 제거합니다. |
| [convert_date_time_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_date_time_data/) | 속성은 파일 내 문자열이 날짜로 변환되는지 여부를 나타냅니다. 기본값은 True입니다. |
| [convert_numeric_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_numeric_data/) | 파일 내 문자열이 숫자 값으로 변환되는지 여부를 나타내는 플래그입니다. 기본값은 True입니다. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owned/) | 문서 컨테이너에 있는 소유 문서를 변환해야 하는지 제어하는 옵션입니다. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owner/) | 문서 컨테이너 자체를 변환해야 하는지 제어하는 옵션입니다; true인 경우 컨테이너가 첫 번째 변환 문서가 됩니다. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/default_font/) | 폰트가 없을 경우 사용할 폰트. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/depth/) | 깊이 옵션은 변환을 수행할 깊이 레벨 수를 제어합니다. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/encoding/) | CSV 파일에 사용되는 인코딩입니다. 기본값은 `Encoding.Default`입니다. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/font_substitutes/) | 폰트 대체. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/format/) | 입력 문서 파일 유형입니다. |
| [has_formula](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/has_formula/) | 속성은 텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다. |
| [is_multi_encoded](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/is_multi_encoded/) | 속성은 파일에 여러 인코딩이 포함되어 있는지 여부를 나타냅니다. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/margin_settings/) | 페이지 여백 설정. |
| [separator](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/separator/) | CSV 파일의 구분자입니다. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/size_settings/) | 페이지 크기 설정. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/skip_external_resources/) | 속성은 외부 리소스가 로드되는지 여부를 나타냅니다. True인 경우, [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) 목록에 있는 리소스를 제외한 모든 외부 리소스가 로드되지 않습니다. 기본값: True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/whitelisted_resources/) | 항상 로드되는 외부 리소스. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | 이 속성은 시트의 모든 열 내용이 결과에서 단일 페이지에 렌더링되는지 여부를 결정합니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | 변환 시 행이 자동 맞춤됩니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | 이 속성은 셀 관련 객체를 수정할 때 Excel 파일 제한이 확인되는지 여부를 결정합니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | 워크시트를 페이지로 나누는 데 사용되는 페이지당 열 수; 기본값은 0이며 페이지 매김을 비활성화합니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | 스프레드시트가 아닌 형식으로 변환할 때 변환할 범위, 예: "D1:F8". ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | 파일이 로드될 때 사용되는 시스템 문화 정보입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | 이 속성은 수식 계산 오류를 무시할지 여부를 나타냅니다. 오류는 지원되지 않는 함수, 외부 링크 등일 수 있습니다. 기본값은 False입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | 이 속성은 각 시트의 내용이 PDF 문서에서 단일 페이지로 변환되는지 여부를 나타냅니다. 기본값은 True입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | True로 설정하면 PDF로 변환할 때 인쇄 품질보다 파일 크기 감소에 최적화됩니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | 보호된 문서의 보호를 해제하는 데 사용되는 비밀번호입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | PDF로 변환할 때 문서 구조를 보존할지 여부를 나타내는 플래그입니다 (기본값은 False). ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | 시트와 함께 주석이 인쇄되는 방식입니다. 기본값은 PrintNoComments입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | 문서를 로드하기 전에 글꼴 폴더가 재설정됩니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | 워크시트를 페이지로 분할하는 데 사용되는 페이지당 행 수이며, 기본값 0은 페이지 구분이 없음을 의미합니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | 변환할 시트 인덱스 목록입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | 변환할 시트 이름입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Excel 파일을 변환할 때 눈금선을 표시하는 옵션입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Excel 파일을 변환할 때 숨겨진 시트를 표시하는 옵션입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | 변환 시 빈 행과 열을 건너뛰는 설정입니다. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | 이 속성은 스프레드시트 문서를 변환할 때 바닥글을 건너뛸지 여부를 결정합니다. 기본값: False. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | 스프레드시트 문서를 변환할 때 머리글을 건너뛰는 옵션입니다. 기본값: False. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)에서 상속됨) |

### 또 보기
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
