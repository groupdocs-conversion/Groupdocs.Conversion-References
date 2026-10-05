---
title: "SpreadsheetFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Spreadsheet 문서를 정의합니다."
type: docs
weight: 25
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

스프레드시트 문서를 정의합니다. 다음 파일 형식을 포함합니다: [Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Csv), [Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Fods), [Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Ods), [Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Ots), [Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Tsv), [Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlam), [Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xls), [Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlsb), [Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlsm), [Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlsx), [Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlt), [Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xltm), [Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xltx). 스프레드시트 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/spreadsheet
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SpreadsheetFileType()](#SpreadsheetFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Xls](#Xls) | XLS는 Excel 이진 파일 형식을 나타냅니다. |
| [Xlsx](#Xlsx) | XLSX는 Microsoft Office 2007 출시와 함께 Microsoft에서 도입한 Microsoft Excel 문서에 대한 잘 알려진 형식입니다. |
| [Xlsm](#Xlsm) | XLSM은 매크로를 지원하는 스프레드시트 파일 유형입니다. |
| [Xlsb](#Xlsb) | XLSB 파일 형식은 Excel 이진 파일 형식을 지정하며, 이는 Excel 워크북 내용을 지정하는 레코드와 구조의 컬렉션입니다. |
| [Ods](#Ods) | ODS 확장자를 가진 파일은 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 나타냅니다. |
| [Ots](#Ots) | .ots 확장자를 가진 파일은 Apache OpenOffice에 포함된 Calc 애플리케이션 소프트웨어로 만든 OpenDocument 스프레드시트 템플릿 파일입니다. |
| [Xltx](#Xltx) | XLTX 파일은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿을 나타냅니다. |
| [Xlt](#Xlt) | .XLT 확장자를 가진 파일은 Microsoft Office 제품군의 일부인 스프레드시트 애플리케이션 Microsoft Excel로 만든 템플릿 파일입니다. |
| [Xltm](#Xltm) | XLTM 파일 확장자는 Microsoft Excel에서 매크로 사용 템플릿 파일로 생성된 파일을 나타냅니다. |
| [Tsv](#Tsv) | 탭으로 구분된 값(TSV) 파일 형식은 탭으로 구분된 데이터를 일반 텍스트 형식으로 나타냅니다. |
| [Xlam](#Xlam) | XLAM은 스프레드시트에 새로운 기능을 추가하는 매크로 사용 추가 기능 파일입니다. |
| [Csv](#Csv) | CSV(Comma Separated Values) 확장자를 가진 파일은 쉼표로 구분된 값이 포함된 레코드 데이터를 가진 일반 텍스트 파일을 나타냅니다. |
| [Fods](#Fods) | .fods 확장자를 가진 파일은 행과 열에 데이터를 저장하는 OpenDocument 스프레드시트 문서 형식의 일종입니다. |
| [Dif](#Dif) | DIF는 서로 다른 애플리케이션 간에 스프레드시트 데이터를 가져오고 내보내는 데 사용되는 데이터 교환 형식을 의미합니다. |
| [Sxc](#Sxc) | SXC(Sun XML Calc) 파일 형식은 OpenOffice.org라는 오피스 제품군에 속합니다. |
| [Numbers](#Numbers) | .numbers 확장자를 가진 파일은 스프레드시트 파일 유형으로 분류됩니다. 그 때문에 .xlsx 파일과 유사하지만 Numbers 파일은 Apple iWork Numbers 스프레드시트 소프트웨어를 사용하여 생성됩니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


직렬화 생성자

### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS는 Excel Binary File Format을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 생성될 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/xls

### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX는 Microsoft Office 2007 출시와 함께 Microsoft에서 도입한 Microsoft Excel 문서용 널리 알려진 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM은 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


XLSB 파일 형식은 Excel Binary File Format을 지정하며, 이는 Excel 워크북 내용을 지정하는 레코드와 구조의 모음입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


ODS 확장자를 가진 파일은 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 의미합니다. 데이터는 ODF 파일 내부에 행과 열로 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/ods

### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


.ots 확장자를 가진 파일은 Apache OpenOffice에 포함된 Calc 애플리케이션 소프트웨어로 생성된 OpenDocument 스프레드시트 템플릿 파일입니다. Calc 애플리케이션 소프트웨어는 Microsoft Office에서 제공되는 Excel과 유사합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/ots

### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


XLTX 파일은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿을 나타냅니다. 이는 XLTX 파일에 지정된 동일한 설정을 가진 XLSX 파일을 생성하는 데 사용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


.XLT 확장자를 가진 파일은 Microsoft Office 제품군의 일부인 Microsoft Excel로 만든 템플릿 파일입니다. Microsoft Office 97-2003은 새로운 XLT 파일을 만들고 열 수 있었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


XLTM 파일 확장자는 Microsoft Excel에서 매크로 사용 템플릿 파일로 생성된 파일을 나타냅니다. XLTM 파일은 구조적으로 XLTX와 유사하지만, 후자는 매크로가 포함된 템플릿 파일 생성을 지원하지 않습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


탭으로 구분된 값(TSV) 파일 형식은 탭으로 구분된 데이터를 일반 텍스트 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM은 스프레드시트에 새로운 기능을 추가하는 매크로 사용 추가 기능 파일입니다. Add-In은 추가 코드를 실행하고 스프레드시트에 추가 기능을 제공하는 보조 프로그램입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://docs.fileformat.com/spreadsheet/xlam/

### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


CSV(Comma Separated Values) 확장자를 가진 파일은 쉼표로 구분된 값이 포함된 레코드 데이터를 가진 일반 텍스트 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/csv

### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


.fods 확장자를 가진 파일은 행과 열에 데이터를 저장하는 OpenDocument 스프레드시트 문서 형식의 일종입니다. 이 형식은 OASIS에서 발행 및 유지 관리하는 ODF 1.2 사양의 일부로 지정됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/fods

### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF는 서로 다른 애플리케이션 간에 스프레드시트 데이터를 가져오고 내보내는 데 사용되는 데이터 교환 형식을 의미합니다. 여기에는 Microsoft Excel, OpenOffice Calc, StarCalc 및 기타 많은 프로그램이 포함됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/dif

### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


SXC(Sun XML Calc) 파일 형식은 OpenOffice.org라는 오피스 제품군에 속합니다. 이 형식은 XML 기반 스프레드시트 파일 형식으로 사용자의 스프레드시트 요구를 일반적으로 처리합니다. SXC 형식은 수식, 함수, 매크로 및 차트와 함께 DataPilot을 지원합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][]를 참조하십시오.


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


.numbers 확장자를 가진 파일은 스프레드시트 파일 유형으로 분류됩니다. 그래서 .xlsx 파일과 유사합니다; 하지만 Numbers 파일은 Apple iWork Numbers 스프레드시트 소프트웨어를 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/numbers

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


파일 유형에 대한 기본 변환 옵션을 준비했습니다.

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
