---
title: "compress 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 결과를 압축합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/compress/
is_root: false
weight: 1010
---


## compress {#options}

변환 결과를 압축합니다.

반환된 인터페이스에서 더 이상 사용되지 않는 fluent 체인 메서드를 사용하는 대신, 엔트리 단계에서 [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (설정 `OnCompressionCompleted`)을 통해 압축‑스트림 핸들러를 등록합니다.

```python
def compress(self, options):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 압축 변환 옵션. |

**Returns:** Continuation that proceeds to `Convert`.

### 또 보기
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
