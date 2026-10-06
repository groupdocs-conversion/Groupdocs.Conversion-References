---
title: "with_options 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "로드 옵션을 설정합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/with_options/
is_root: false
weight: 1100
---


## with_options {#load_options}

로드 옵션을 설정합니다.

```python
def with_options(self, load_options):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| load_options | `LoadOptions` | 로드 옵션 |

## with_options {#load_options_provider}

현재 로드 중인 문서에 대한 로드 옵션을 제공합니다.

```python
def with_options(self, load_options_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | 로드 옵션 제공자. 로드 옵션 컨텍스트. |

### 또 보기
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
