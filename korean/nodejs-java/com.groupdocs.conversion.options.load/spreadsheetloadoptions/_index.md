---
title: "SpreadsheetLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Spreadsheet 문서를 로드하기 위한 옵션."
type: docs
weight: 35
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable
```

Spreadsheet 문서를 로드하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | 새 인스턴스를 초기화합니다 [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSheets()](#getSheets--) | 변환할 시트 이름을 가져옵니다 |
| [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | 변환할 시트 이름을 설정합니다 |
| [getCultureInfo()](#getCultureInfo--) | 파일이 로드될 때 시스템 문화 정보를 가져옵니다 |
| [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | 파일이 로드될 때 시스템 문화 정보를 설정합니다 |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | 스프레드시트 문서의 기본 글꼴입니다. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | 스프레드시트 문서의 기본 글꼴입니다. |
| [getFontSubstitutes()](#getFontSubstitutes--) | 스프레드시트 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | 스프레드시트 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [getShowGridLines()](#getShowGridLines--) | Excel 파일을 변환할 때 눈금선을 표시합니다. |
| [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Excel 파일을 변환할 때 눈금선을 표시합니다. |
| [getShowHiddenSheets()](#getShowHiddenSheets--) | Excel 파일을 변환할 때 숨겨진 시트를 표시합니다. |
| [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Excel 파일을 변환할 때 숨겨진 시트를 표시합니다. |
| [getOnePagePerSheet()](#getOnePagePerSheet--) | OnePagePerSheet가 true이면 시트의 내용이 PDF 문서에서 한 페이지로 변환됩니다. |
| [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | OnePagePerSheet가 true이면 시트의 내용이 PDF 문서에서 한 페이지로 변환됩니다. |
| [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | AllColumnsInOnePagePerSheet 속성을 가져옵니다. |
| [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | AllColumnsInOnePagePerSheet 속성을 설정합니다. |
| [getOptimizePdfSize()](#getOptimizePdfSize--) | True이고 PDF로 변환하는 경우, 변환이 인쇄 품질보다 파일 크기를 줄이도록 최적화됩니다. |
| [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | True이고 PDF로 변환하는 경우, 변환이 인쇄 품질보다 파일 크기를 줄이도록 최적화됩니다. |
| [getConvertRange()](#getConvertRange--) | 스프레드시트 형식이 아닌 다른 형식으로 변환할 때 특정 범위를 변환합니다. |
| [setConvertRange(String value)](#setConvertRange-java.lang.String-) | 스프레드시트 형식이 아닌 다른 형식으로 변환할 때 특정 범위를 변환합니다. |
| [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | 변환 시 빈 행과 열을 건너뜁니다. |
| [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | 변환 시 빈 행과 열을 건너뜁니다. |
| [getPassword()](#getPassword--) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
| [getHideComments()](#getHideComments--) | 주석을 숨깁니다. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | 주석을 숨깁니다. |
| [isCheckExcelRestriction()](#isCheckExcelRestriction--) | 사용자가 셀 관련 객체를 수정할 때 Excel 파일의 제한을 확인할지 여부입니다. |
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
| [getSheetIndexes()](#getSheetIndexes--) | 변환할 시트 인덱스 목록을 가져옵니다. |
| [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | 변환할 시트 인덱스 목록을 설정합니다. |
| [isAutoFitRows()](#isAutoFitRows--) | 변환 시 모든 행을 자동 맞춤합니다. |
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
| [getResetFontFolders()](#getResetFontFolders--) | 문서를 로드하기 전에 폰트 폴더를 재설정합니다 |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
| [deepClone()](#deepClone--) | 현재 인스턴스를 복제합니다. |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


새 인스턴스를 초기화합니다 [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) 클래스.

### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


변환할 시트 이름을 가져옵니다

**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


변환할 시트 이름을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 시트 | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


파일이 로드될 때 시스템 문화 정보를 가져옵니다

**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


파일이 로드될 때 시스템 문화 정보를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


입력 문서 파일 유형

**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


스프레드시트 문서의 기본 글꼴입니다. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


스프레드시트 문서의 기본 글꼴입니다. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


스프레드시트 문서를 변환할 때 특정 글꼴을 대체합니다.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


스프레드시트 문서를 변환할 때 특정 글꼴을 대체합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Excel 파일을 변환할 때 눈금선을 표시합니다.

**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Excel 파일을 변환할 때 눈금선을 표시합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Excel 파일을 변환할 때 숨겨진 시트를 표시합니다.

**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Excel 파일을 변환할 때 숨겨진 시트를 표시합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


OnePagePerSheet가 true이면 시트의 내용이 PDF 문서에서 한 페이지로 변환됩니다. 기본값은 false입니다.

**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


OnePagePerSheet가 true이면 시트의 내용이 PDF 문서에서 한 페이지로 변환됩니다. 기본값은 false입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


AllColumnsInOnePagePerSheet 속성을 가져옵니다.

**Returns:**
boolean - 모든 열을 한 페이지에 맞추면 true
### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


AllColumnsInOnePagePerSheet 속성을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| allColumnsInOnePagePerSheet | boolean | AllColumnsInOnePagePerSheet 속성 |

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


True이고 PDF로 변환하는 경우, 변환이 인쇄 품질보다 파일 크기를 줄이도록 최적화됩니다.

**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


True이고 PDF로 변환하는 경우, 변환이 인쇄 품질보다 파일 크기를 줄이도록 최적화됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


스프레드시트 형식이 아닌 다른 형식으로 변환할 때 특정 범위를 변환합니다. 예: "D1:F8".

**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


스프레드시트 형식이 아닌 다른 형식으로 변환할 때 특정 범위를 변환합니다. 예: "D1:F8".

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


변환 시 빈 행과 열을 건너뜁니다. 기본값은 True입니다.

**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


변환 시 빈 행과 열을 건너뜁니다. 기본값은 True입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


주석을 숨깁니다.

**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


주석을 숨깁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


사용자가 셀 관련 객체를 수정할 때 Excel 파일의 제한을 확인할지 여부입니다. 예를 들어, Excel은 32KB보다 긴 문자열 입력을 허용하지 않습니다. 32KB보다 긴 값을 입력하면 이 속성이 true일 경우 예외가 발생합니다. 이 속성이 false이면 입력한 문자열 값을 셀 값으로 받아들여 나중에 CSV와 같은 다른 파일 형식으로 전체 문자열 값을 출력할 수 있습니다. 그러나 Excel 파일 형식에 유효하지 않은 값을 설정한 경우 이후에 워크북을 Excel 파일 형식으로 저장하면 안 됩니다. 그렇지 않으면 생성된 Excel 파일에서 예상치 못한 오류가 발생할 수 있습니다.

**Returns:**
boolean - 제한 확인 플래그
### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


변환할 시트 인덱스 목록을 가져옵니다.

**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


변환할 시트 인덱스 목록을 설정합니다. 인덱스는 0부터 시작해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


변환 시 모든 행을 자동 맞춤합니다.

**Returns:**
boolean
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| autoFitRows | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


문서를 로드하기 전에 폰트 폴더를 재설정합니다

**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


현재 인스턴스를 복제합니다.

**Returns:**
java.lang.Object -
