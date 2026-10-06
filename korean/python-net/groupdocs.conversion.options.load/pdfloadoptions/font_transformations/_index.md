---
title: "font_transformations 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "문서 로드 및 글꼴 대체 후 적용되는 글꼴 변환으로, 로드에 성공한 글꼴을 포함한 문서 내 모든 글꼴을 수정할 수 있습니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/pdfloadoptions/font_transformations/
is_root: false
weight: 2090
---


## font_transformations property

문서 로드 및 글꼴 대체 후 적용되는 글꼴 변환으로, 로드에 성공한 글꼴을 포함한 문서 내 모든 글꼴을 수정할 수 있습니다.

참고: 글꼴 변환은 모든 글꼴 대체 단계가 완료된 후에 적용됩니다.

변환은 목록에 나타나는 순서대로 처리됩니다.

사용 사례: 스타일링 변경, 브랜드 요구사항, 접근성 향상.

### Definition:
```python
@property
def font_transformations(self):
    ...
@font_transformations.setter
def font_transformations(self, value):
    ...
```

### 또 보기
* class [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/)
