---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "스프레드시트 문서를 정의합니다. 다음 파일 유형을 포함합니다 Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. 스프레드시트 형식에 대해 자세히 알아보려면 여기https//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /ko/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

스프레드시트 문서를 정의합니다. 다음 파일 유형을 포함합니다: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xl sm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). 스프레드시트 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet).

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
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 유형 설명 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 패밀리 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 객체를 다른 객체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | `[`Equals`](../../groupdocs.conversion.contracts/enumeration/equals)`를 구현합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수로 사용됩니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | CSV (Comma Separated Values) 확장자를 가진 파일은 쉼표로 구분된 값이 포함된 레코드 데이터를 담은 일반 텍스트 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/csv)를 클릭하십시오. |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF는 서로 다른 애플리케이션 간에 스프레드시트 데이터를 가져오거나 내보내는 데 사용되는 데이터 교환 형식(Data Interchange Format)을 의미합니다. 여기에는 Microsoft Excel, OpenOffice Calc, StarCalc 및 기타 많은 프로그램이 포함됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/dif)를 클릭하십시오. |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel은 ZIP 패키지가 아닌 평면 XML 파일에 저장된 Office Open XML SpreadsheetML입니다. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | .fods 확장자를 가진 파일은 행과 열에 데이터를 저장하는 OpenDocument 스프레드시트 문서 형식의 일종입니다. 이 형식은 OASIS에서 발행하고 유지 관리하는 ODF 1.2 사양의 일부로 정의됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/fods)를 클릭하십시오. |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | .numbers 확장자를 가진 파일은 스프레드시트 파일 유형으로 분류되며, 따라서 .xlsx 파일과 유사합니다; 그러나 Numbers 파일은 Apple iWork Numbers 스프레드시트 소프트웨어를 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/spreadsheet/numbers)를 클릭하십시오. |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | ODS 확장자를 가진 파일은 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식이며, 데이터가 ODF 파일 내부의 행과 열에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/ods)를 클릭하십시오. |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | .ots 확장자를 가진 파일은 Apache OpenOffice에 포함된 Calc 응용 프로그램 소프트웨어로 생성된 OpenDocument 스프레드시트 템플릿 파일입니다. Calc 응용 프로그램 소프트웨어는 Microsoft Office에서 제공되는 Excel과 유사합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/ots)를 클릭하십시오. |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | SXC(Sun XML Calc) 파일 형식은 OpenOffice.org라는 오피스 제품군에 속합니다. 이 형식은 XML 기반 스프레드시트 파일 형식으로 사용자의 스프레드시트 요구를 처리합니다. SXC 형식은 수식, 함수, 매크로, 차트 및 DataPilot을 지원합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/sxc)를 클릭하십시오. |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | TSV(탭 구분 값) 파일 형식은 탭으로 구분된 데이터를 일반 텍스트 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/tsv)를 클릭하십시오. |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM은 스프레드시트에 새로운 기능을 추가하는 매크로 사용 가능 추가 기능 파일입니다. 추가 기능은 추가 코드를 실행하고 스프레드시트에 추가 기능을 제공하는 보조 프로그램입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/spreadsheet/xlam/)를 클릭하십시오. |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS는 Excel 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 생성될 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xls)를 클릭하십시오. |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB 파일 형식은 Excel 바이너리 파일 형식을 지정하며, 이는 Excel 통합 문서 내용을 지정하는 레코드와 구조의 모음입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xlsb)를 클릭하십시오. |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM은 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xlsm)를 클릭하십시오. |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX는 Microsoft Office 2007 출시와 함께 Microsoft가 도입한 Microsoft Excel 문서의 잘 알려진 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xlsx)를 클릭하십시오. |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | .XLT 확장자를 가진 파일은 Microsoft Office 제품군의 일부인 스프레드시트 애플리케이션 Microsoft Excel로 만든 템플릿 파일입니다. Microsoft Office 97-2003은 새로운 XLT 파일을 만들고 열 수 있었습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xlt)를 클릭하십시오. |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM 파일 확장자는 Microsoft Excel에서 매크로 사용 가능 템플릿 파일로 생성된 파일을 나타냅니다. XLTM 파일은 구조적으로 XLTX와 유사하지만, 후자는 매크로가 포함된 템플릿 파일을 만들 수 없습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xltm) 를 클릭하십시오. |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX 파일은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿을 나타냅니다. 이는 동일한 설정을 가진 XLSX 파일을 생성하는 데 사용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xltx)를 클릭하십시오. |

### 또 보기

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
