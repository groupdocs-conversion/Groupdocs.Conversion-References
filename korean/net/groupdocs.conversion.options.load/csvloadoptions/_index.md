---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "CSV 문서를 로드하기 위한 옵션."
type: docs
weight: 2450
url: /ko/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

CSV 문서를 로드하기 위한 옵션.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | 새 인스턴스를 초기화합니다 [`CsvLoadOptions`](../csvloadoptions) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | AllColumnsInOnePagePerSheet가 true이면, 하나의 시트에 있는 모든 열 내용이 결과에서 한 페이지에만 출력됩니다. 페이지 설정의 용지 크기 너비는 무효화되지만, 페이지 설정의 다른 항목은 여전히 적용됩니다. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | 변환 시 모든 행을 자동 맞춤합니다. |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | 사용자가 셀 관련 객체를 수정할 때 Excel 파일의 제한을 검사할지 여부입니다. 예를 들어, Excel은 32K보다 긴 문자열 입력을 허용하지 않습니다. 32K보다 긴 값을 입력하면 이 속성이 true일 경우 예외가 발생합니다. 이 속성이 false이면 입력 문자열 값을 셀 값으로 받아들여 나중에 CSV와 같은 다른 파일 형식으로 전체 문자열 값을 출력할 수 있습니다. 그러나 Excel 파일 형식에 유효하지 않은 값을 설정한 경우 이후에 워크북을 Excel 파일 형식으로 저장하면 안 됩니다. 그렇지 않으면 생성된 Excel 파일에 예상치 못한 오류가 발생할 수 있습니다. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | 문서에서 기본 메타데이터 속성을 제거합니다. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | 문서에서 사용자 정의 메타데이터 속성을 제거합니다. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | 워크시트를 열 기준으로 페이지로 분할합니다. 기본값은 0이며 페이지 매김이 없습니다. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | 파일의 문자열이 날짜로 변환되는지 여부를 나타냅니다. 기본값은 True입니다. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | 파일의 문자열이 숫자로 변환되는지 여부를 나타냅니다. 기본값은 True입니다. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | `[`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned)`을 구현합니다. 기본값은 false입니다. |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | `[`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner)`을 구현합니다. 기본값은 true입니다. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | 스프레드시트 형식이 아닌 다른 형식으로 변환할 때 특정 범위를 변환합니다. 예: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | 파일이 로드될 때 시스템 문화 정보를 가져오거나 설정합니다. |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | 스프레드시트 문서의 기본 글꼴입니다. 글꼴이 없을 경우 다음 글꼴이 사용됩니다. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | `[`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth)`을 구현합니다. 기본값: 1 |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | 인코딩. 기본값은 Encoding.Default입니다. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | 스프레드시트 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [Format](../../groupdocs.conversion.options.load/csvloadoptions/format) { get; } | 입력 문서 파일 유형. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 입력 문서 파일 유형. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | 텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다. |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | 수식 계산 오류를 무시할지 여부를 나타냅니다. 오류는 지원되지 않는 함수, 외부 링크 등일 수 있습니다. 기본값은 false입니다. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True는 파일에 여러 인코딩이 포함되어 있음을 의미합니다. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | 페이지 여백 설정 |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | OnePagePerSheet가 true이면 시트 내용이 PDF 문서의 한 페이지로 변환됩니다. 기본값은 true입니다. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | True이고 PDF로 변환하는 경우, 인쇄 품질보다 파일 크기를 줄이도록 변환이 최적화됩니다. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | PDF로 변환할 때 문서 구조를 보존할지 여부를 결정합니다(기본값은 false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | 시트와 함께 주석이 인쇄되는 방식을 나타냅니다. 기본값은 PrintNoComments입니다. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | 문서를 로드하기 전에 글꼴 폴더를 재설정합니다. |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | 워크시트를 행 기준으로 페이지로 분할합니다. 기본값은 0이며 페이지 매김이 없습니다. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Csv 파일의 구분자입니다. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | 변환할 시트 인덱스 목록입니다. 인덱스는 0부터 시작해야 합니다. |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | 변환할 시트 이름 |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Excel 파일을 변환할 때 그리드 라인을 표시합니다. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Excel 파일을 변환할 때 숨겨진 시트를 표시합니다. |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | 페이지 크기 설정 |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | 변환 시 빈 행과 열을 건너뜁니다. 기본값은 True입니다. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | 구현 [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | 스프레드시트 문서를 변환할 때 바닥글을 건너뜁니다. 기본값: false. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | 스프레드시트 문서를 변환할 때 헤더를 건너뜁니다. 기본값: false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | 구현 [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | 현재 인스턴스를 복제합니다. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 기본 해시 함수로 사용됩니다. |

### 또 보기

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
