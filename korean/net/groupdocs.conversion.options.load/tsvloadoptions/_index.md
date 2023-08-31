---
title: TsvLoadOptions
second_title: .NET API 참조용 GroupDocs.Conversion
description: Tsv 문서 로드 옵션.
type: docs
weight: 2280
url: /ko/net/groupdocs.conversion.options.load/tsvloadoptions/
---
## TsvLoadOptions class

Tsv 문서 로드 옵션.

```csharp
public sealed class TsvLoadOptions : SpreadsheetLoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TsvLoadOptions](tsvloadoptions)() | 의 새 인스턴스를 초기화합니다.[`TsvLoadOptions`](../tsvloadoptions) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | 사용자가 셀 관련 개체를 수정할 때 엑셀 파일의 제한 여부를 확인합니다. 예를 들어 Excel에서는 32K보다 긴 문자열 값을 입력할 수 없습니다. 32K보다 긴 값을 입력할 때 이 속성이 true이면 Exception이 발생합니다. 이 속성이 false이면 나중에 CSV와 같은 다른 파일 형식에 대한 전체 문자열 값을 출력할 수 있도록 입력 문자열 값을 셀 값으로 수락합니다. 단, 엑셀 파일 형식에 맞지 않는 값을 설정한 경우에는 워크북을 나중에 엑셀 파일 형식으로 저장하면 안됩니다. 그렇지 않으면 생성된 엑셀 파일에 예기치 않은 오류가 발생할 수 있습니다. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | 스프레드시트 형식이 아닌 다른 형식으로 변환할 때 특정 범위를 변환합니다. 예: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | 파일이 로드될 때 시스템 문화 정보를 가져오거나 설정합니다 |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | 스프레드시트 문서의 기본 글꼴. 글꼴이 누락된 경우 다음 글꼴이 사용됩니다. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | 스프레드시트 문서를 변환할 때 특정 글꼴로 대체합니다. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | 입력 문서 파일 유형. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 입력 문서 파일 유형. |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | 댓글을 숨깁니다. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | OnePagePerSheet가 참이면 시트의 내용이 PDF 문서의 한 페이지로 변환됩니다. 기본값은 true입니다. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | True이고 PDF로 변환하면 인쇄 품질보다 더 나은 파일 크기에 맞게 변환이 최적화됩니다. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | 보호된 문서의 보호를 해제하려면 암호를 설정하십시오. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | 변환할 시트 인덱스 목록입니다. 인덱스는 0부터 시작해야 합니다 |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | 변환할 시트 이름 |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Excel 파일을 변환할 때 격자선을 표시합니다. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Excel 파일 변환 시 숨겨진 시트 표시. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | 변환 시 빈 행과 열을 건너뜁니다. 기본값은 True입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | 현재 인스턴스를 복제합니다. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 기본 해시 함수 역할을 합니다. |

### 또한보십시오

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* 네임스페이스 [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->