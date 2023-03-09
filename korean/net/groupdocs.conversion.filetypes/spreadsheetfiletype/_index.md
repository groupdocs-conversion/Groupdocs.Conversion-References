---
title: SpreadsheetFileType
second_title: .NET API 참조용 GroupDocs.Conversion
description: 스프레드시트 문서를 정의합니다. 다음 파일 형식을 포함합니다. Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . 스프레드시트 형식에 대해 자세히 알아보기여기https//wiki.fileformat.com/spreadsheet .
type: docs
weight: 1050
url: /ko/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

스프레드시트 문서를 정의합니다. 다음 파일 형식을 포함합니다. [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . 스프레드시트 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | 직렬화 생성자 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 형식 description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 개체를 다른 개체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 개체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수 역할을 합니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | CSV(쉼표로 구분된 값) 확장자가 있는 파일은 쉼표로 구분된 값이 있는 데이터 레코드가 포함된 일반 텍스트 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF는 서로 다른 응용 프로그램 간에 스프레드시트 데이터를 가져오거나 내보내는 데 사용되는 데이터 교환 형식을 나타냅니다. 여기에는 Microsoft Excel, OpenOffice Calc, StarCalc 등이 포함됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | 확장자가 .fods인 파일은 행과 열에 데이터를 저장하는 일종의 OpenDocument 스프레드시트 문서 형식입니다. 형식은 OASIS에서 게시하고 유지 관리하는 ODF 1.2 사양의 일부로 지정됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/fods) . |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | 확장자가 .numbers인 파일은 스프레드시트 파일 유형으로 분류되므로 .xlsx 파일과 유사합니다. 하지만 Numbers 파일은 Apple iWork Numbers 스프레드시트 소프트웨어를 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | 확장자가 ODS인 파일은 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 나타냅니다. 데이터는 ODF 파일 내부에 행과 열로 저장됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | 확장자가 .ots인 파일은 Apache OpenOffice에 포함된 Calc 응용 소프트웨어로 생성되는 OpenDocument 스프레드시트 템플릿 파일입니다. Calc 응용 프로그램 소프트웨어는 Microsoft Office에서 사용할 수 있는 Excel과 유사합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/ots) . |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | 파일 형식 SXC(Sun XML Calc)는 OpenOffice.org라는 오피스 제품군에 속합니다. 이 형식은 일반적으로 XML 기반 스프레드시트 파일 형식이므로 사용자의 스프레드시트 요구를 처리합니다. SXC 형식은 DataPilot. 와 함께 공식, 함수, 매크로 및 차트를 지원합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/sxc) . |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | TSV(Tab-Separated Values) 파일 형식은 탭으로 구분된 데이터를 일반 텍스트 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM은 스프레드시트에 새 기능을 추가하는 데 사용되는 매크로 사용 추가 기능 파일입니다. 추가 기능은 추가 코드를 실행하고 스프레드시트에 대한 추가 기능을 제공하는 추가 프로그램입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/xlam/) . |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS는 Excel 이진 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 기타 유사한 스프레드시트 프로그램으로 만들 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB 파일 형식은 Excel 통합 문서 내용을 지정하는 레코드 및 구조 모음인 Excel 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM은 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX는 Microsoft Office 2007 릴리스와 함께 Microsoft에서 도입한 잘 알려진 Microsoft Excel 문서 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | 확장자가 .XLT인 파일은 Microsoft Office 제품군의 일부로 제공되는 스프레드시트 응용 프로그램인 Microsoft Excel로 만든 템플릿 파일입니다. Microsoft Office 97-2003은 새 XLT 파일 생성 및 열기를 지원했습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM 파일 확장자는 Microsoft Excel에서 생성된 파일을 매크로 사용 템플릿 파일로 나타냅니다. XLTM 파일은 XLTX가 매크로로 템플릿 파일 생성을 지원하지 않는다는 점을 제외하면 구조상 XLTX와 유사합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX 파일은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿을 나타냅니다. XLTX 파일에 지정된 것과 동일한 설정을 나타내는 XLSX 파일을 생성하는 데 활용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xltx) . |

### 또한보십시오

* class [FileType](../filetype)
* 네임스페이스 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 집회 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
