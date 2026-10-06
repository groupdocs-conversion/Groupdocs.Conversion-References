---
title: "layout_names 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환될 레이아웃 이름."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

변환될 레이아웃 이름.

PDF/UA-1로 변환할 때는 적용되지 않습니다. 해당 대상은 도면을 단일 태그 페이지로 렌더링하므로 선택된 레이아웃당 한 장을 포함할 수 없으며, 따라서 전체 도면이 대신 변환되고 여기의 내용은 적용되지 않습니다.

PDF를 포함한 다른 모든 대상은 선택을 존중합니다. 이러한 대상에서는 이름이 도면이 포함하는 레이아웃과 정확히 일치하도록 매칭되므로, 대소문자만 다른 이름은 다른 이름으로 간주됩니다. 일치하는 것이 없는 이름은 제외되며 호출자에게는 해당 시트만 비용이 발생합니다; 아무 것도 일치하지 않는 목록은 변환을 실패시키며, `InvalidLoadOptionsException`을 발생시켜 누락된 이름과 도면이 실제로 포함하고 있는 레이아웃을 명시합니다. 호출자가 요청하지 않은 시트를 렌더링하지 않습니다. 도면에 레이아웃이 전혀 없는 경우는 예외이며, 매칭할 이름이 없으므로 어떤 것도 거부되지 않습니다.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### 또 보기
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
