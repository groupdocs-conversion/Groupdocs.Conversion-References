---
title: "compress 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 결과를 압축합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/compress/
is_root: false
weight: 1010
---


## compress {#options}

변환 결과를 압축합니다.

엔트리 단계에서 압축된 스트림 핸들러를 [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (설정 `OnCompressionCompleted`)을 통해 등록하고, 반환된 인터페이스의 오래된 fluent 체인 메서드를 사용하지 마십시오.

```python
def compress(self, options):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | `CompressionConvertOptions` | 압축 변환 옵션 |

**Returns:** Continuation that proceeds to `Convert`.

### 또 보기
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
