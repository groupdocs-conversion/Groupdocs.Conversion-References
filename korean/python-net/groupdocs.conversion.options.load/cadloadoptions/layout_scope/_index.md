---
title: "layout_scope 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환되는 도면 공간을 결정하는 레이아웃 범위."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

변환되는 그리기 공간을 결정하는 레이아웃 범위. 기본값은 [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)이며, 변환을 제한하지 않습니다. [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/)이 제공되면 무시됩니다. 이는 명시적인 레이아웃 이름이 항상 우선하기 때문입니다. `None` 값은 [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)으로 처리됩니다.

범위가 도면이 제공하는 시트 중 어느 것도 선택하지 않으면, 변환은 `InvalidLoadOptionsException`으로 실패하며, 이 예외는 제외된 공간을 렌더링하는 대신 범위와 사용 가능한 시트의 이름을 표시합니다. 시트를 전혀 제공하지 않는 도면은 영향을 받지 않으며 여전히 단일 단위로 변환됩니다. PDF/UA-1로 변환할 때는 적용되지 않으며, 그 이유는 [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/)에 설명되어 있습니다.

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### 또 보기
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
