---
title: "compress 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 결과를 압축합니다; 압축된 스트림 핸들러를 진입 단계에서 IConversionSettings.withevents 를 통해 등록하고(`OnCompressionCompleted` 설정) 오래된 fluent 메서드 사용 대신."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

변환 결과를 압축합니다; 구식 유창 체인 메서드 대신 [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/)를 통해 진입 단계에서 압축 스트림 핸들러를 등록합니다(`OnCompressionCompleted` 설정).

```python
def compress(self, options):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 압축 변환 옵션. |

**Returns:** Continuation that proceeds to `Convert`.

### 또 보기
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
