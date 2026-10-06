---
title: "cap_resolution_to_page_content 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "이 속성은 페이지별 PDF 렌더링 해상도를 페이지의 기본 래스터 해상도로 제한하여, 삽입된 이미지보다 높은 DPI로 렌더링되는 것을 방지하고 페이지를 기본(작은) 해상도로 출력합니다…"
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

이 속성은 페이지별 PDF 렌더링 해상도를 페이지의 기본 래스터 해상도로 제한하여, 삽입된 이미지보다 높은 DPI로 렌더링되는 것을 방지하고 최종 출력에서 페이지를 기본(작은) 픽셀 크기와 DPI로 출력합니다.

이미지 중심(스캔) 페이지에만 적용됩니다; 텍스트나 벡터 콘텐츠가 있는 페이지는 절대 부드럽게 처리되지 않으며 요청된 DPI로 출력됩니다. 명시적인 출력 [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) 또는 [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/)가 설정된 경우에는 제한이 무시됩니다. 기본값은 False이며(제한 없음; 모든 페이지가 요청된 DPI로 렌더링 및 출력됩니다).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### 또 보기
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
