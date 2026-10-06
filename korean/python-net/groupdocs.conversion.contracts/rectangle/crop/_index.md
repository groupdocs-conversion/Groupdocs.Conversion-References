---
title: "crop 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "지정된 여백을 제거하여 현재 Rectangle의 잘린 버전을 생성합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.contracts/rectangle/crop/
is_root: false
weight: 1010
---


## crop {#crop_left-crop_top-crop_right-crop_bottom}

지정된 여백을 제거하여 현재 Rectangle의 잘린 버전을 생성합니다.

```python
def crop(self, crop_left, crop_top, crop_right, crop_bottom):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| crop_left | `int` | 왼쪽에서 제거할 픽셀 수. |
| crop_top | `int` | 위쪽에서 제거할 픽셀 수. |
| crop_right | `int` | 오른쪽에서 제거할 픽셀 수. |
| crop_bottom | `int` | 아래쪽에서 제거할 픽셀 수. |

**Returns:** Rectangle: A new cropped rectangle.

### 또 보기
* class [`Rectangle`](/conversion/python-net/groupdocs.conversion.contracts/rectangle/)
