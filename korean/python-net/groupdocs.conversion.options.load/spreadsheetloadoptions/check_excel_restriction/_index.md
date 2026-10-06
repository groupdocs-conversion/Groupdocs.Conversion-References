---
title: "check_excel_restriction 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "이 속성은 셀 관련 객체를 수정할 때 Excel 파일 제한이 확인되는지 여부를 결정합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

이 속성은 셀 관련 객체를 수정할 때 Excel 파일 제한이 확인되는지 여부를 결정합니다.

true이면 32 K보다 긴 문자열을 입력하려고 하면 예외가 발생합니다. false이면 입력 문자열이 허용되어 전체 값을 CSV와 같은 다른 형식으로 출력할 수 있습니다. 그러나 이러한 잘못된 값을 포함한 워크북을 Excel 형식으로 다시 저장하면 예상치 못한 오류가 발생할 수 있습니다.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### 또 보기
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
